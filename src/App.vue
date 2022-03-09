<template>
  <div id="app">
   <MainHeader/>
   <JumboTron/>
   <MainInfo/>
   <MainFooter/>
   <SignUp/>
  </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue'
import JumboTron from './components/JumboTron.vue'
import MainInfo from './components/MainInfo.vue'
import MainFooter from './components/MainFooter.vue'
import SignUp from './components/SignUp.vue'


export default {
  name: 'App',
  components: {
    MainInfo,
    MainHeader,
    JumboTron,
    MainFooter,
    SignUp,
   
  }
}
</script>

<style lang="scss">

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
ul,ol{
  list-style: none;
}
#app{
  max-width:1920px ;
  
}


</style>
