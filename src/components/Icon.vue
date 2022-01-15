.<template>

    <li>
        <img :id="small" :src="src" alt="">
        {{text}}
    </li>
    

           
</template>

<script>
export default {
    name: "Icon",
    props: ["src","text","small"]
}
</script>

<style lang="scss" scoped>
   @import "./../assets/scss/partials/_icon.scss"
</style>