<template>
  <div class="contact-info">
    main footer
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
  background-image: url('../assets/img/dc-logo-bg.png'),url('../assets/img/footer-bg.jpg');
  background-repeat: no-repeat;
  background-size:contain ,cover;
  background-position: right center;
  }


</style>
