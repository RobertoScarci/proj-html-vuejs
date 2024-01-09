<script>
  import AppHeader from './components/AppHeader.vue';
  import AppMain from './components/AppMain.vue';
  import AppFooter from './components/AppFooter.vue';
  import AppPlane from './components/AppPlane.vue';
  
  export default {
    name: "AppVue",
    components: {
      AppHeader,
      AppMain,
      AppFooter,
      AppPlane
    }
  }
</script>

<template>
  <AppHeader/>
  <AppMain/>
  <AppPlane/>
  <AppFooter/>
</template>

<style lang="scss">
  @use '../node_modules/bootstrap/scss/bootstrap.scss' as *;
  @use "./styles/general.scss" as *;
</style>
