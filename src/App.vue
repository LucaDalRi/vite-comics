<script>
import AppHeader from './components/AppHeader.vue';
import AppMainSection1 from './components/AppMainSection1.vue';
import AppMainSection2 from './components/AppMainSection2.vue'
import AppFooterSection1 from './components/AppFooterSection1.vue';
import AppFooterSection2 from './components/AppFooterSection2.vue';

export default {
  name: "App",
  components: {
    AppHeader,
    AppMainSection1,
    AppMainSection2,
    AppFooterSection1,
    AppFooterSection2,

  }
};
</script>

<template>
  <AppHeader />
  <AppMainSection1 />
  <AppMainSection2 />
  <AppFooterSection1/>
  <AppFooterSection2 />
</template>

<style lang="scss" scoped>

</style>
