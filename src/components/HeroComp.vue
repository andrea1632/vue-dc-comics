<template>
    <div class="container">
        <div class="imgContainer" v-for="(elm, index) in imageList" :key="index">
            <img :src="elm.url" :alt="elm.name">
            <span>{{elm.name}}</span>
        </div>
    </div>
</template>

<script> 
export default{
    name: 'HeroComp',
    data: function(){
        return{
            imageList:[
                {
                    'url': require('../assets/img/buy-comics-digital-comics.png'), 
                    'name': 'digital comics',
                },
                {
                    'url': require('../assets/img/buy-comics-merchandise.png'),
                    'name': 'dc merchandise',
                },
                {
                    'url': require('../assets/img/buy-comics-shop-locator.png'),
                    'name': 'comic shop locator'
                },
                {
                    'url': require('../assets/img/buy-comics-subscriptions.png'),
                    'name': 'subscriptions'
                },
                {
                    'url': require('../assets/img/buy-dc-power-visa.svg'),
                    'name': 'dc power visa'
                }
        ]
        }
    }
}
</script>
<style scoped>
img{
    width: 100%;
}
.imgContainer{
    display: flex;
    align-items: center;
    width: 70px;
}
span{
    color: white;
    text-transform: uppercase;
    font-size: 0.8em;
    min-width: 200px;
}
.container{
    display: flex;
    justify-content: space-around;
    padding: 50px 0;
    width: 80%;
    margin: 0 auto;
}
</style>
