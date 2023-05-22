<script>
    import NavbarApp from './NavbarApp.vue';
    export default {
    components: {
      NavbarApp,
    }
    }
</script>

<template>
  <header>
    <div class="container">
      <img src="../assets/img/dc-logo.png" alt="">
      <NavbarApp />
    </div>
  </header>
</template>

<style scoped>
    header{
    width: 100%;
    height: 130px;
    }

    .container {
      width: 1000px;
      margin: auto;
      display: flex;
    }

    img{
        height: 90px;
    } 
</style>
