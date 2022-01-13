.<template>
  <footer>
      <div class="back-contact">
        <div class="container">
            <div class="contact">
                <div>
                     <h2>DC COMICS</h2>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                
                    <h2>SHOP</h2>

                    <ul>
                        <li>
                            Shop DC 
                        </li>
                        <li>
                            Shop DC Collectibles
                        </li>
                    </ul>

                </div>
                
                <div>
                    <h2>DC</h2>
                    <ul>
                        <li>Terms of Use</li>
                        <li>Privacy policy (new)</li>
                        <li>Ad Choice</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshop</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>
                
                <div>
                    <h2>SITES</h2>
                    <ul>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
                
            </div>
            <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
        
      </div>

      <div class="sign-up">
          <div class="container">
              <button>
                  SiGN-UP NOW!
              </button>
              <div class="follow-us">
                  <h3>FOLLOW US</h3>
                  <ul>
                      <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                      <li>
                          <img src="../assets/img/footer-twitter.png" alt="">
                      </li>
                      <li><img src="../assets/img/footer-youtube.png" alt=""></li>
                      <li>
                          <img src="../assets/img/footer-pinterest.png" alt="">
                      </li>
                      <li>
                          <img src="../assets/img/footer-periscope.png" alt="">
                      </li>
                  </ul>
              </div>
          </div>
      </div>
     
  </footer>
</template>

<script>
export default {
    name: "Footer",
    data() {
        return {
            
        }
    },
}
</script>

<style lang="scss" scoped>
    .back-contact {
        height: 45vh;
        background-image: url("../assets/img/footer-bg.jpg");
        .container {
            display: flex;
            justify-content: space-between;
            position: relative;
            .contact {
                display: flex;
                justify-content: space-between;
                width: 390px;
                padding: 20px 0;

                ul li {
                    color: #7c7c7c;
                    font-size: 0.8em;
                    margin-bottom: 5px;
                    cursor: pointer;
                    &:hover {
                        color: white;
                    }
                }
                  
            }
            img {
                position: absolute;
                right: 0;
                top: -70px;
                width: 30em;
            }            
        }
    }

    .sign-up {
        height: 15vh;
        background-color: #303030;
        position: relative;
        z-index: 2;
        
        .container {
            display: flex;
            align-items: center;
            justify-content: space-between;
            height: 100%;
                button {
                cursor: pointer;
                padding: 10px;
                background-color:#303030;
                color: white;
                border: 1px solid blue;
                &:hover {
                    box-shadow: 5px 5px blue
                    }
            }
            .follow-us{
                display: flex;
                align-items: center;
                ul {
                    display: flex;
                    li {
                        margin-left: 15px;
                        cursor: pointer;
                        &:hover {
                            filter: brightness(2);
                        }
                    }
                }
            }
        }
       
    }
</style>