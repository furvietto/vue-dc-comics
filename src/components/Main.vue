.<template>
    <main>
        <div class="content">
            <div class="container">
                <h1>--> Content goes here </h1>
            </div>
        </div>
        <div class="navPage">
            <div class="container">
                <ul>
                    <li>
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                        DIGITAL COMICS
                    </li>
                    <li>
                        <img src="../assets/img/buy-comics-merchandise.png" alt="">
                        DC MERCHANDISE
                    </li>
                    <li>
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                        SUBSCRIPTIONS
                    </li>
                    <li>
                        <img id="small" src="../assets/img/buy-comics-shop-locator.png" alt="">
                        COMIC SHOP LOCATOR
                    </li>
                    <li>
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                        DC POWER VISA
                    </li>
                    
                </ul>
            </div>
        </div>
    </main>
</template>

<script>
export default {
    name: "Main",
    data() {
        return {
            
        }
    },
}
</script>

<style lang="scss" scoped>
main {
    position: relative;
    z-index: 2;
    .content {
    height: 10vh;
    background-color: black;
    color: white;
    display: flex;
    align-items: center;
    }
    .navPage {
        height: 20vh;
        background-color: blue;
        color: white;
        .container {
            height: 100%;
                ul {
                display: flex;
                justify-content: space-around;
                align-items: center;
                height: 100%;
                font-size: 0.7em;
                        li{
                            cursor: pointer;
                            img {
                            margin-right: 10px;
                            width: 45px;
                            vertical-align: middle;
                            } 

                            #small{
                                width: 35px;
                            }
                        } 
                    
                
        }
        }
        
    }
}


</style>