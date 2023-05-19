<script>
    export default{
        name: "AppFooterOne"

    }
</script>
<template>
    <div class="containerSfondo dFlex justifyContentCenter">
        <!-- contenuto sx. -->
        <div class="containerUl dFlex  ">
            <!-- listasx. -->
            <div>
                <h3>DC COMICS</h3>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                </ul>

                <h4>SHOP</h4>
                    <ul>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
            </div>

            <!-- listacenter. -->
            <div>
                <h3>DC </h3>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>                   
                </ul>
            </div>

            <!-- listadx. -->
            <div>
                <h3>SITES</h3>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>                   
                </ul>
            </div>
        </div>

        <!-- blocco immagine. -->
        
        <img src="../assets/dc-logo-bg.png" alt="">
        

    </div>
</template>

<style scoped>
    .containerSfondo {
        background-image: url(../assets/footer-bg.jpg);
        height: 300px;
    }

    *{
        color: white;
        list-style-type: none;
        padding-left: 0;       
        margin-left: 0; 
    }

    li{
        color: rgba(255, 255, 255, 0.5);
        text-decoration: none;
    }

    .containerUl{
        margin-right: 200px;
    }
    .logo{
        margin-right: 120px;
    }

    .containerUl div{
        padding-left: 10px;
    }
</style>