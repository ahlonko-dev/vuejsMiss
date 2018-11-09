<template>
  <div id="app">
    <Mission/>
  </div>
</template>

<script>
import Mission from "./components/Mission";

export default {
  name: "App",
  components: {
    Mission
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
