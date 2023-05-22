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
        <div class="conteinerImg"> 
            <img :src="img" alt="">
            <p>{{ bigText }}</p>
        </div>
    

</template>

<style scoped>

    .mainContent{
        background-color: black;
        width: 100%;
        height: 120px;
    }

    p{
        color: white;
        
    }
    /* .conteinerIm{
        width: 50px;
    } */
    img{
        width: 100px;
    }

    .conteinerImg{
        width: 270px;
    }

</style>