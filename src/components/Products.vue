.<template>
  <li>
    <div class="square">
        <img :src="img" alt="">
    </div>
    <h4>{{series}}</h4>
</li>
</template>

<script>
export default {
    name: "Products",
    props: ["img", "series"]
}
</script>

<style lang="scss" scoped>
   li {
            margin: 20px;
            
            font-size: 0.6em;
            width: calc(100% / 6 - 40px);
            height: 130px;
            cursor: pointer;
            .square {
                overflow: hidden;
                width: 100%;
                height: 100%;
                img{
                width: 100%;
            }
            }
            
        }
</style>