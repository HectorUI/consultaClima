<template>
  <div id="app">
    <Buscador msg="Welcome to Your Vue.js App" />
    <Buscador msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import Buscador from "./components/Buscador";

export default {
  name: "App",
  components: {
    Buscador,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: "montserrat", sans-serif;
}
</style>
