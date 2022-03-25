<template>
  <div class="jumbotron">
    <h1>{{ message }}</h1>
    <img src="../assets/images.jpg" id="size" alt="Hero" />
  </div>
</template>

<script>
export default {
  name: "HeroComponent",
  data() {
    return {
      message: "Sono un Jumbotron",
    };
  },
};
</script>

<style scoped>
.jumbotron {
  margin-top: 50px;
  background-color: blue;
  color: white;
}
#size {
  width: 500px;
  height: 500px;
}
h1 {
  font: bolder;
  font-size: 3em;
}
</style>
