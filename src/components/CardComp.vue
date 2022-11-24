<template>
    <div class="card">
        <img :src="dettagliProdotto.thumb" alt="">
        <h4>{{dettagliProdotto.series.toUpperCase()}}</h4>
    </div>
</template>

<script>
    export default {
        name: 'CardComp',
        props:{
            dettagliProdotto: Object
        }
    }
</script>

<style lang="scss" scoped>
    .card{
        width: calc(100% / 6);
        padding: 15px;
    }
</style>