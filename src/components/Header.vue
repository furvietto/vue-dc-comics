.<template>
  <header>
      <div class="container">
          <img src="../assets/img/dc-logo.png" alt="">
          <ul>
              <li>CHARACTERS</li>
              <li class="active">COMICS</li>
              <li>MOVIES</li>
              <li>TV</li>
              <li>GAMES</li>
              <li>COLLECTIBLES</li>
              <li>VIDEOS</li>
              <li>FANS</li>
              <li>NEWS</li>
              <li>SHOP</li>
          </ul>
      </div>
      <div class="jumbotron">
          <div class="current-series">
              <h1>CURRENT SERIES</h1>
          </div>
      </div>
  </header>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return {
            
        }
    },
}
</script>

<style lang="scss" scoped>
.container {
    height: 10vh;
    font-size: 0.7em;
    padding: 10px 0;
    display: flex;
    justify-content: space-between;
        & > ul {
            display: flex;
            justify-content: center;
            align-items: center;
                li {
                  padding:0 10px;
                  height: 100%;
                  display: flex;
                  align-items: center;
                  border-bottom: 2px solid transparent;  
                  cursor: pointer;
                  &:hover,
                  &:active,
                  &.active{
                      color: blue;
                      border-bottom: 2px solid blue;
                  }
                }
        }
}

.jumbotron {
    height: 40vh;
    background-image: url("../assets/img/jumbotron.jpg");
    background-size: cover ;
    position: relative;
    .current-series {
        position: absolute;
        bottom: -12px;
        left: 220px;
        padding: 10px;
        color: white;
        background-color: blue;
        z-index: 3;
    }
}
</style>