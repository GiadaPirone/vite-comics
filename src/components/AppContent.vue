<script>
    export default{
        name: "AppContent",
        props:{
            img: String,
            bigText:String,
        }
    }
</script>

<template>
    <div class="dFlex">

        <div class="conteinerImg"> 
            <img :src="img" alt="">
            <p>{{ bigText }}</p>
        </div>
    </div>
    

</template>

<style scoped>

    .mainContent{
        background-color: black;
        width: 100%;
        height: 120px;
    }

    h1{
        color: white;
        
    }
    /* .conteinerIm{
        width: 50px;
    } */
    img{
        width: 100px;
    }

</style>