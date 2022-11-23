<template>
    <div>
        <div class="sect">
        <div class="container">
            <span>Content goes here</span>
        </div>

        <div class="sectblue">
            <div class="contblue">
                <div class="box">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMIX</span>
                </div>

                <div class="box">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <span>DC MERCHANDISE</span>
                </div>

                <div class="box">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <span>COMIC SHOP LOCATOR</span>
                </div>

                <div class="box">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <span>SUBSCRIPTIONS</span>
                </div>

                <div class="box">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <span>DC POWER VISA</span>
                </div>
                
            </div>
        </div>
    </div>
    </div>
    
</template>

<script>
    export default {
        name: 'MainComp'
    }
</script>

<style lang="scss" scoped>

    .sect{
        background-color: black;
        color: white;
    }

    .container{
        width: 80%;
        margin: 0 auto;
        padding-top: 60px;
        padding-bottom: 60px;
    }

    .sectblue{
        background-color: lightblue;
        color: white;
    }

    .contblue{
        width: 80%;
        margin: 0 auto;
        padding: 30px;
        display: flex;
        justify-content: space-around;
        align-items: center;

            .box{               
                display: flex;
                align-items: center;
                    
                    img{
                        width: 50px;
                    }
        }
        
    }


</style>