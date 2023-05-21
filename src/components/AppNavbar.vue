<script>
    export default{
        name: "AppNavbar",
        data(){
            return{
                links: [
                    "CHARACTERS",
                    "COMICS",
                    "MOVIES",
                    "TV",
                    "GAMES",
                    "COLLECTIBLES",
                    "VIDEOS",
                    "FANS",
                    "NEWS",
                    "SHOP",
                ]
            }
        }

    }
</script>

<template>
    <div class="navBar dFlex spaceAround">
        <!-- logo. -->
        <div class="dFlex alignCenter">
            <img  src="../assets/dc-logo.png" alt="">
        </div>
        <!-- barramenu. -->
        <div class="dFlex alignCenter">

            <p class="linksMenu" v-for="link in links">{{ link }}</p>
            
            <!-- <p>CHARACTERS</p>             
            <p>COMICS</p>            
            <p>MOVIES</p>
            <p>TV</p>
            <p>GAMES</p>
            <p>COLLECTIBLES</p>
            <p>VIDEOS</p>
            <p>FANS</p>
            <p>NEWS</p>
            <p>SHOP</p> -->

        </div>
        
    </div>
</template>

<style scoped>
    .navBar{
        
        height: 100px;
        width: 100%;
    }

    img{
        width: 80%;
    }

    p{
        padding: 0px 15px 0px 15px;
    }
    p:hover{
        color: #0282F9;
    }

</style>
