<template>
  <signuopForm></signuopForm>
</template>

<script>
import signuopForm from "./components/signuopForm.vue";

export default {
  name: "App",
  components: { signuopForm },
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

body {
  margin: 0;
  background: #eee;
}
</style>
