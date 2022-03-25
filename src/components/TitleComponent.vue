<template>
  <div class="header">
    <h1>{{ message }}</h1>
  </div>
</template>

<script>
export default {
  name: "TitleComponent",
  data() {
    return {
      message: "La mia prima app con Vue CLI!",
    };
  },
};
</script>

<style scoped>
h1 {
  font-size: 2em;
  line-height: 124px;
}
.header {
  background-color: red;
}
</style>
