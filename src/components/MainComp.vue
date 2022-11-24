<template>
    <div>
        <div class="sect">
        <div class="container">
            <CardComp />
            <button>CURRENT SERIES</button>
        </div>

        <div class="contcards">
            <div class="cards">

            </div>
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

    import CardComp from './CardComp.vue'
    export default {
       
        name: 'MainComp',
        components: {
            CardComp,
        }
    }
</script>

<style lang="scss" scoped>

    .sect{
        background-color: black;
        color: white;
    }

    .container{
        background-image: url('../assets/img/jumbotron.jpg');
        height: 500px;
        padding-top: 60px;
        padding-bottom: 60px;

        button{
            margin-top: 420px;
            padding: 10px 15px;
            color: white;
            background-color: rgba(2, 130, 249, 1);
            border: none;
        }
    }

    .sectblue{
        background-color: rgba(2, 130, 249, 1);
        color: white;
        /* z-index: 2; */
        
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

                span{
                    margin-left: 10px;
                }
                    
                    img{
                        width: 50px;
                    }
        }
        
    }

    .contcards{
        background-color: rgba(28, 28, 28, 1);

        .cards{
            width: 80%;
            margin: 0 auto;
        }
    }


</style>