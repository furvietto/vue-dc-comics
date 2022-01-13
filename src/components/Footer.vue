.<template>
  <footer>
      <div class="container">
        <div class="contact">
            <ul>
                <li>
                    <h2>DC COMICS</h2>
                </li>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
                <li>
                    <h2>SHOP</h2>
                </li>
                <li>
                    Shop DC 
                </li>
                <li>
                    Shop DC Collectibles
                </li>
            </ul>

            <ul>
                <li>
                    <h2>DC</h2>
                </li>
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
            <ul>
                <li>
                    <h2>
                        SITES
                    </h2>
                </li>
                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
            </ul>
        </div>
        <img src="../assets/img/dc-logo-bg.png" alt="">
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
    footer {
        height: 40vh;
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
                }
                  
            }
            img {
                position: absolute;
                right: 0;
                top: -100px;
                width: 30em;
            }            
        }
    }
</style>