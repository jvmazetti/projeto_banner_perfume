<template>
    <a class="hero__adicionar">
        <img src="../images/carrinho.png"/>
        <p>Add to Cart</p>
    </a>
</template>

<style scoped>
    .hero__adicionar{
        margin-top: 0;
        border-radius: 10px;
        background-color: green;
        margin-bottom:60px;
        margin-top: 0;
        cursor:pointer;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .hero__adicionar p {   
        width: 100%;
        cursor: pointer; 
        font-family: Arial, Helvetica, sans-serif;
        font-weight: bold;
        font-size:25px; 
        color: black;
        margin:center;
    }
    .hero__adicionar img{
        max-height:30px;
        align-items: center;
        justify-content: center;
        margin-right: 5px;
        margin-left: 100px;
        margin-bottom: 8px;
    }
</style>