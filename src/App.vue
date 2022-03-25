<template>
  <div id="app">
    <TitleComponent />
    <HeroComponent />
  </div>
</template>

<script>
import TitleComponent from "./components/TitleComponent.vue";
import HeroComponent from "./components/HeroComponent.vue";
export default {
  name: "App",
  components: {
    TitleComponent,
    HeroComponent,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
}
</style>
