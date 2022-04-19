<template>
    <div class="container">
        <HeroContent/>
        <div>
            <span class="currentSeries">
                <strong>current series</strong>
            </span>
        </div>
    </div>
</template>

<script>
import HeroContent from './HeroContent.vue'
export default{
    name: 'ContentComp',
    components: {
        HeroContent,
    }, 
}
</script>

<style scoped>
    .currentSeries{
        background-color: #0282F9;
        padding: 20px;
        color: white;
        text-transform: uppercase;
        border: 1 px solid red;
    }
</style>