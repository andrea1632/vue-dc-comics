<template>
    <div class="container">
        <div>
            <img src="img/dc-logo.png" alt="">
        </div>
        <ul>
            <li v-for="(elm, index) in headerList" :key="index">
                <a :href="elm.ref">{{elm.name}}</a>
            </li>
        </ul>
    </div>
</template>



<script> 

export default{
    name: 'HeaderComp',
    data: function () {
  return {
    headerList: [
        {
            'name': 'character',
            'ref': '/character',
        },
               {
            'name': 'comics',
            'ref': '/comics',
        },
               {
            'name': 'movies',
            'ref': '/movies',
        },
               {
            'name': 'tv',
            'ref': '/tv',
        },
               {
            'name': 'games',
            'ref': '/games',
        },
               {
            'name': 'collectibles',
            'ref': '/collectibles',
        },
               {
            'name': 'videos',
            'ref': '/videos',
        },
               {
            'name': 'fans',
            'ref': '/fans',
        },
               {
            'name': 'news',
            'ref': '/news',
        },
                {
            'name': 'shop',
            'ref': '/shop',
        },
    ]
  }
}
}



</script>

<style scooped>
    li{
        list-style: none;
        margin: 0 10px;
        
    }
    .container{
        display: flex;
        width: 80%;
        margin: 0 auto;
        justify-content: space-between;
    }
    a{
        text-transform: uppercase;
        text-decoration: none;
        color: black;
        font-weight: 600;
        padding-bottom: 42px;
    }
    ul{
        display: flex;
        align-items: center;
    }
    a:hover{
        border-bottom: 3px solid #0282F9;
        color: #0282F9;
    }
</style>