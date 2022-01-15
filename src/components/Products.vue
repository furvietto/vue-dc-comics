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
  @import "./../assets/scss/partials/_product.scss"
</style>