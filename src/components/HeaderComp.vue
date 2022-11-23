<template>
    <div class="sect">
        <div class="container">
            <div>
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <div class="nav">
                <span>CHARACTERS</span>
                <span class="blue">COMIX</span>
                <span>MOVIES</span>
                <span>TV</span>
                <span>GAMES</span>
                <span>COLLECTIBLES</span>
                <span>VIDEOS</span>
                <span>FANS</span>
                <span>NEWS</span>
                <span>SHOP</span>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'HeaderComp',
    }
</script>

<style lang="scss" scoped>
.container{
    width: 80%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px;
}

span{
    margin: 0 15px;
    cursor: pointer;
}

.blue{
    color: blue;
    
}

</style>