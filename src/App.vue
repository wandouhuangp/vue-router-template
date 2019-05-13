<template>
  <div id="app">
    <PageA/>
  </div>
</template>

<script>
import PageA from "./components/PageA";
import PageB from "./components/PageB";
export default {
  name: "App",
  components: {
    PageA,
    PageB
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
