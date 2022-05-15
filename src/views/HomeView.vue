<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <ContainerDer
      titulo="Mas del 90% es plastico"
      msg="El 90% de la basura que flota en el mar es material plasticos, alrededor de 13 millones de toneladas de vertidas en los océanos cada año, esto afecta a especies marinas, rios y lagos."
    />
    <ContainerIzq
      titulo="Trafico ilegal de especies marinas"
      descripcion="De acuerdo a diferentes Organizaciones No Gubernamentales se calcula que la delincuencia organizada obtiene entre 10 mil y 20 mil millones de dólares anuales por el tráfico global de biodiversidad terrestre y se desconoce a cuánto asciende la depredación de las especies marinas, la codicia de una actividad ilegal que crece y empeora."
    />
    <ContainerModel
      titulo="Neptuno X Project"
      descripcion="Mediante las nuevas tecnologias, hemos diseñado un robot que funcionara mediante una aplicacion movil que se encargue de recolectar el plastico que se encuentra en el mar"
    />
    <HelloWorld msg="Hola soy helloworld" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import ContainerDer from "../components/ContainerDer.vue";
import ContainerIzq from "../components/ContainerIzq.vue";
import ContainerModel from "../components/ContainerModel.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
    ContainerDer,
    ContainerIzq,
    ContainerModel,
  },
};
</script>
