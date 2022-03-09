<template>
    <div class="info-wrapper">
       <div class="info">
           <ul>
               <li v-for="(card,index) in cards"  :key="index">
                   <img :src="card.imgUrl" alt="">
                    {{card.text}}
                    
               </li>
           </ul>
       </div>
    </div>
</template>

<script>
export default {
   name: 'MainInfo',
   props: {
    msg: String
  },
  data() {
    return {
        cards :[
            {
                text: 'DIGITAL COMICS',
                imgUrl: require('../assets/img/buy-comics-digital-comics.png')
            },
            {
                text: 'DC MERCHANDISE',
                imgUrl: require('../assets/img/buy-comics-merchandise.png')
            },
            {
                text: 'SUBSCRIPTION',
                imgUrl: require('../assets/img/buy-comics-subscriptions.png')
            },
            {
                text: 'COMIC SHOP LOCATOR',
                imgUrl: require('../assets/img/buy-comics-shop-locator.png')
            },
            {
                text: 'DC POWER VISA',
                imgUrl: require('../assets/img/buy-dc-power-visa.svg')
            },

        ]

    }
  }
}
  
</script>

<style scoped lang="scss">
.info-wrapper{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 153px;
    background-color:#0282f9 ;

        ul{
            display: contents;
    }
  .info{
        color:white;
        display: flex;
        gap: 56px;
        justify-content: center;
        align-items: center;
        li{
            display: flex;
            align-items: center;
            gap:18px;
            img{
                height: 56px;
            }
        }
  }
}
</style>
