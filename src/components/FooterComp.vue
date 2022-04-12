<template>
    <div class="container">
        <div>
            <a href="#">SIGN UP NOW!</a>
        </div>
        <div class="socials">
            <h4>FOLLOW US</h4>
        <div>
            <img src="img/footer-facebook.png" alt="">
        </div>
        <div>
            <img src="img/footer-twitter.png" alt="">
        </div>
        <div>
            <img src="img/footer-youtube.png" alt="">
        </div>
        <div>
            <img src="img/footer-pinterest.png" alt="">
        </div>
        <div>
            <img src="img/footer-periscope.png" alt="">
        </div>
        </div>
    </div>
</template>

<script>
export default{
    name: 'FooterComp',
}
</script>

<style scoped>
    .container{
        width: 80%;
        margin: 0 auto;
        padding: 40px 0;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    a{
        padding: 10px;
        border: 2px solid #0282F9;
        text-decoration: none;
        color: white;
    }
    h4{
        color: #0282F9;
    }
    .socials{
        display: flex;
        align-items: center;
    }
    .socials div{
        margin: 0 10px;
    }
</style>