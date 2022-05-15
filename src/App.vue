<template>
  <Navbar />
  <router-view />
</template>

<script>
import Navbar from "./components/NavBar.vue";

export default {
  name: "App",
  components: {
    Navbar,
  },
};
</script>

<style>
:root {
  --text-color: #3232;
  --text-color-alt: #214258;
  --bg-color: rgba(255, 255, 255, 0.459);
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-size: 100% 100%;
  background-repeat: no-repeat;
  background: url("./assets/background/fondoweb.png");
  background-size: cover;
}

ul {
  list-style: none;
}

a {
  text-decoration: none;
  color: initial;
}
</style>
