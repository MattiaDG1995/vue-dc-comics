<template>
    <div>
        <div class="sectdc">
            <div class="cont">
                <div class="contlist">
                    <div class="list">
                        <div>
                            <h4>DC COMICS</h4>
                            <P>lorem</P>
                            <P>lorem</P>
                            <P>lorem</P>
                            <P>lorem</P>
                            <P>lorem</P>
                            <P>lorem</P>
                            <P>lorem</P>
                        </div>

                        <div class="listbottom">
                            <h4>SHOP</h4>
                            <p>lorem</p>
                            <p>lorem</p>
                        </div>
                    </div>

                    <div class="list">
                        <h4>DC</h4>
                        <p>lorem</p>
                        <p>lorem</p>
                        <p>lorem</p>
                        <p>lorem</p>
                        <p>lorem</p>
                        <p>lorem</p>
                        <p>lorem</p>
                        <p>lorem</p>
                        <p>lorem</p>
                        <p>lorem</p>
                        <p>lorem</p>
                    </div>

                    <div class="list">
                        <h4>SITES</h4>
                        <p>lorem</p>
                        <p>lorem</p>
                        <p>lorem</p>
                        <p>lorem</p>
                        <p>lorem</p>
                    </div>
                                       
                </div>
                
                <div class="logo">
                    <!-- <img src="../assets/img/dc-logo-bg.png" alt=""> -->
                </div>
            </div>
        </div>

        <div class="sectSign">
            <div class="contSign">
                <div class="footright">
                    <h4>SIGN-UP NOW!</h4>
                </div>

                <div class="footleft">
                    <h4>FOLLOW US</h4>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'FooterComp'
    }
</script>

<style lang="scss" scoped>

.sectdc{
    background-image: url('../assets/img/footer-bg.jpg');
    overflow: hidden;
}

.cont{
    width: 80%;    
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    
    

    .logo{
        background-image: url('../assets/img/dc-logo-bg.png');
        width: 50%;
        background-repeat: no-repeat;
        background-position: 20px;
    }

    .contlist{
        display: flex;
        padding-top: 30px;
        padding-bottom: 30px;
    }

    .list{
        margin-right: 50px;
    }
        h4{
            color: white;
            margin-bottom: 10px;
        }

        p{
            color: gray;
            margin-bottom: 3px;
        }

        .listbottom{
            margin-top: 20px;
        }
      
}

.sectSign{
        background-color: rgba(48, 48, 48, 1);
        /* z-index: 1; */
            
        }

        .contSign{
            width: 80%;    
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding-top: 30px;
            padding-bottom: 30px;

            .footright h4{
                border: 1px solid rgba(2, 130, 249, 1);
                padding: 10px;
                color: white;
            }

            .footleft{
                display: flex;
                align-items: center;

                h4{
                    margin-right: 20px;
                    color: rgba(2, 130, 249, 1);
                }
                img{
                    padding: 10px;
                }
            }
                    
        }
</style>