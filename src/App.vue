<template>
  <div id="app">
    <DBanner/>
    <img alt="Vue logo" src="./assets/logo.png">
  </div>
</template>

<script>
import DBanner from "./components/DBanner.vue";

export default {
  name: "app",
  components: {
    DBanner
  }
};
</script>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
