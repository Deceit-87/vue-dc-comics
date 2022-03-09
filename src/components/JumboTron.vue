<template>
  <div class="jumbotron">
    jumbotron  
  </div>
</template>

<script>
export default {
  name: 'JumboTron',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss">
.jumbotron{
    color: white;
    background: black;
     min-height: 135px;
}
</style>