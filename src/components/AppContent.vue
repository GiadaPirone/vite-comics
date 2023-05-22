<script>
    export default{
        name: "AppContent",
        props:[
            "slide"
        ]
            
    
        // data(){
        //     return{
        //         slides: [
        //             {
        //                 thumb: "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
        //                 series: "Action Comics",
        //             },

        //             {
        //                 thumb: "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
        //                 series: "American Vampire 1976",
        //             },
        //         ]
        //     }
        // }

    }
</script>

<template>
    <div class="mainContent dFlex alignCenter justifyContentCenter">
        <h1> Content goes here </h1>
    </div>
    <div v-for="testo in slide">
        <div >{{ testo }}</div>
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
</style>