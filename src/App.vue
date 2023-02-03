<script>
import AppHeader from './components/AppHeader.vue';
import AppMainSection1 from './components/AppMainSection1.vue';
import AppMainSection2 from './components/AppMainSection2.vue'

export default {
  name: "App",
  components: {
    AppHeader,
    AppMainSection1,
    AppMainSection2
  }
};
</script>

<template>
  <AppHeader />
  <AppMainSection1 />
  <AppMainSection2 />
</template>

<style lang="scss" scoped>

</style>
