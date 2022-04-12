<template>
    <div class="container">
        <div class="column">
            <h4>DC COMICS</h4>
            <ul>
                <li>Charcter</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>Tv</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
            </ul>
            <h4>SHOP</h4>
            <ul>
                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>
            </ul>
        </div>
        <div class="column">
            <h4>DC</h4>
            <ul>
                <li>Terms Of Use</li>
                <li>Privacy</li>
                <li>Ad Choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscriptions</li>
                <li>Talent Workshops</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop Help</li>
                <li>Contact Us</li>
            </ul>
        </div>
        <div class="column">
            <h4>SITES</h4>
            <ul>
                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
            </ul>
        </div>
    </div>
</template>

<script> 
export default{
    name: 'MainComp',
}
</script>

<style scoped>
    li{
        list-style: none;
        text-align: left;
        font-size: 0.8em;
        color: #959595;
    }
    h4{
        margin: 20px 0;
        color: white;
    }
    .column{
        display: flex;
        flex-direction: column;
        text-align: left;
        margin: 0 40px;
    }
    .container{
        display: flex;
        padding: 10px 0;
        width: 80%;
        margin: 0 auto;
    }
</style>