<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
    <i class="bx bxl-meta"></i>
  </nav>
  <router-view />
</template>

<style>
:root {
  --text-color: #3232;
  --text-color-alt: #5dadee2;
  --bg-color: #d0d3d4;
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
}

ul {
  list-style: none;
}

a {
  text-decoration: none;
  color: initial;
}
</style>
