<script>

  import AppHeaderVue from './components/AppHeader.vue';
  import AppMainVue from './components/AppMain.vue';
  import AppFooterVue from './components/AppFooter.vue';

  export default {
    data() {
      return {

      }
    },
    components: {
      AppHeaderVue,
      AppMainVue,
      AppFooterVue
    },
    methods: {

    }
  }
</script>

<template>

  <div>

    <AppHeaderVue />
    <AppMainVue />
    <AppFooterVue />

  </div>
  
</template>

<style lang="scss" scoped>
@use "assets/scss/main.scss" as *;
@import "assets/scss/partials/reset.scss";

</style>
