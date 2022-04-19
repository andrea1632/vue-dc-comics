<template>
    <div class="card">
        <div class="imgContainer">
            <img :src="details.thumb" alt="">
        </div>
        <span>
            {{details.series}}
        </span>
    </div>
</template>

<script>
export default{
    name: 'CardListComp', 
    props: ['details']
}
</script>

<style scoped>
    span{
        color :white;
        text-transform: uppercase;
        margin: 15px 0;
        display: inline-block;
        max-width: 250px;
    }
    img{
        width: 100%;
        height: 100%;
    }
    .imgContainer{
    height: 250px;
    width: 220px;
    }
    .card{
    margin-bottom: 50px;
    }
</style>