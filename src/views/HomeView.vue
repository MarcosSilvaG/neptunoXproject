<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <ContainerDer msg="Welcome to Your Vue.js App" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import ContainerDer from "../components/ContainerDer.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
    ContainerDer,
  },
};
</script>
