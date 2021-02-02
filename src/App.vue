<template>
  <HelloWorld />
  <div
    hidden
    id="snipcart"
    data-api-key="NWE5OWVhMjYtYTNmMi00MWE1LWFkMzMtYWMwNTk5ZjJlZDFiNjM3NDc2MDE2MDIzOTIyMjk2"
  ></div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
