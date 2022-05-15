<template>
  <div class="home">
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
    <RecycleContainer
      titulo="De basura a un beneficio"
      descripcion="Todo el plastico recolectado puede tener un segundo fin gracias a las tecnologias con las que contamos y pueden ser de buen provecho para ayudar al ecosistema."
    />
    <HelloWorld msg="Hola soy helloworld" />
  </div>
</template>

<script>
// @ is an alias to /src
import ContainerDer from "../components/ContainerDer.vue";
import ContainerIzq from "../components/ContainerIzq.vue";
import ContainerModel from "../components/ContainerModel.vue";
import RecycleContainer from "../components/RecycleContainer.vue";

export default {
  name: "HomeView",
  components: {
    ContainerDer,
    ContainerIzq,
    ContainerModel,
    RecycleContainer,
  },
};
</script>
<style>
.home {
  padding: 15% 0% 0% 0%;
}
h1 {
  /*Afecta a todos los titulos h1*/
  -webkit-text-stroke: 2px white;
  font-size: 4.5vw;
  font-weight: bold;
  vertical-align: middle;
  color: rgb(16, 37, 73);
}

p {
  /*afecta a todos los parrafos P*/
  font-size: 1.5vw;
  font-weight: 500;
  color: rgb(255, 255, 255);
}
</style>
