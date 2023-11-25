<template>
    <div class="hero__price">
        <h1>$149.99</h1>
        <h5>$169.99</h5>
    </div>
</template>

<style scoped>
    .hero__price{
        display: flex; 
        align-items: center; 
        padding-top: 0px;
        padding-bottom: 0px;
        margin-top: 0;
        margin-bottom: 0;
    }

    .hero__price h1{
        margin-right: 30px;
        font-family: 'Times New Roman', Times, serif;
        font-size: 50px;
        color:black;
    }

    .hero__price h5{
        font-family: 'Times New Roman', Times, serif;
        font-size: 20px;
        color: gray;
        text-decoration: line-through;
    }
</style>