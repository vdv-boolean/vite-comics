<script>
  import HeaderApp from './components/HeaderApp.vue';
  import MainApp from './components/MainApp.vue';
  import FooterApp from './components/FooterApp.vue';
  export default {
    components: {
      HeaderApp,
      FooterApp,
      MainApp,
    }
  }
</script>

<template>
  <HeaderApp/>

  <MainApp />

  <FooterApp/>
</template>

<style scoped>

</style>
