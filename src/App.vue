<script setup>
    import ImagemDoPerfume from './components/ImagemDoPerfume.vue';
    import DescriçãoDoProduto from './components/DescriçãoDoProduto.vue';
    import Preço from './components/Preço.vue';
    import BotaoAdicionarAoCarrinho from './components/BotaoAdicionarAoCarrinho.vue';
</script>

<template>
  <div class="container">
        <section class="hero">
            <ImagemDoPerfume/>
            <div class="hero__description">
                <DescriçãoDoProduto/>
                <Preço/>
                <BotaoAdicionarAoCarrinho/>
            </div>
        </section>
</div>
</template>

<style scoped>
    .container{
        max-width:1024px;
        align-items: center;
        justify-content:center;
        margin:auto;
    }
   .hero{
        width:100%;
        display: flex;
   } 

   .hero__description{
        margin-left: 40px;
    }
   
</style>
