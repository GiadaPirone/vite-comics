<script>
    export default{
        name: "AppMenu"

    }
</script>

<template>
    <div class="mainMenu dFlex justifyContentCenter">
        
            <div class="dFlex">
                <img src="../assets/buy-comics-digital-comics.png" alt="">
                <p>DIGITAL COMICS</p>
            </div>
            <div class="dFlex">
                <img src="../assets/buy-comics-merchandise.png" alt="">
                <p>DC MERCANDISE</p>
            </div>
            <div class="dFlex">
                <img src="../assets/buy-comics-subscriptions.png" alt="">
                <p>SUBSCRIPTION</p>
            </div>
            <div class="dFlex">
                <img src="../assets/buy-comics-shop-locator.png" alt="">
                <p>COMIC SHOP LOCATOR</p>
            </div>
            <div class="dFlex">
                <img src="../assets/buy-dc-power-visa.svg" alt="">
                <p>DC POWER VISA</p>
            </div>
        

    </div>
</template>

<style scoped>
    .mainMenu{
        width: 100%;
        height: 150px;
        background-color:#0282F9 ;
    }

    img{
        height: 30%;
    }

    p{
        color: white;
        margin-left: 15px;
    }
    
    .mainMenu div {
        margin-left: 50px;
        align-items: center;
    }

</style>