<script>
    export default{
        name: "AppFooter"

    }
</script>
<template>
    <div class="footer dFlex alignCenter spaceAround">

        <!-- bottone -->
        <div>
            <button>SING-UP NOW!</button>
        </div>

        <div class="dFlex">
            <p>FOLLOW US</p>
            <div>
                <img src="../assets/footer-facebook.png" alt="">
                <img src="../assets/footer-twitter.png" alt="">
                <img src="../assets/footer-youtube.png" alt="">
                <img src="../assets/footer-pinterest.png" alt="">
                <img src="../assets/footer-periscope.png" alt="">
            </div>
        </div>
        
    </div>
</template>

<style scoped>
    .footer{
        height: 100px;
        background-color: #303030;
    }

    img{
        padding: 0px 5px 0px 5px
    }

    p{
        color:#0282F9 ;
    }

    button {
        height: 40px;
        border: solid 1px #0282F9;
        background-color: #303030;
        color: #fff;
    }
    
</style>