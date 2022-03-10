<template>
  <div class="card-wrapper">
      <img :src="img" >
      <h2>{{title}}</h2>
  </div>
</template>

<script>
export default {
    props: ['img','title']
}
</script>

<style scoped lang="scss">

.card-wrapper{
    width: 15%;
    img{
        width: 100%;
        object-position: top;
        object-fit: cover;
        aspect-ratio: 1/1;
    }
    h2{
        font-size: 12px;
    }
}
</style>