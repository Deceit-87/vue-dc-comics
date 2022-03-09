<template>
  <div class="contact-info">
    <div class="container-footer">
    </div> 
  </div>
</template>

<script>
export default {
  name: 'MainFooter',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss">
  .contact-info{
    height: 481px;
    background-image: url('../assets/img/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
  }
  .container-footer{
    background-image: url('../assets/img/dc-logo-bg.png');
    background-repeat: no-repeat;
    background-position: right;
    height: 482px;
    background-size: initial;
    margin: 0 200px;

  }


</style>
