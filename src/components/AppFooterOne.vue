<script>
    export default{
        name: "AppFooterOne"

    }
</script>

<template>
    <div class="containerSfondo dFlex ">
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
        <div class="conteinerImg">
            <img src="../assets/dc-logo-bg.png" alt="">
        </div>
        

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
        padding-left: 450px;
    }
    .containerUl div{
        padding-left: 10px;
    }

    .conteinerImg{
        position: relative;
        padding-left: 375px;
    
    }

    img{
        position: absolute;
        bottom: -63px;
        width:444px ;
    }
</style>