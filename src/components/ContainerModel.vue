<template>
  <div class="infocontainer2">
    <!--Apartado donde sale la informacion "Why should i vaccine?-->
    <div class="container-info">
      <h2>Why should I vaccine?</h2>
    </div>
    <div class="container-info">
      <p class="p3">
        In order to avoid any doubts about getting the COVID-19<br />vaccine,
        indentify the following 4 benefits of COVID-19<br />vaccination:
      </p>
    </div>
    <div class="container-info"></div>
  </div>
  <!--Termina why should i vaccines-->
</template>

<script>
export default {
  name: "ContainerModel",
  props: {
    titulo: String,
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  color: rgb(31, 62, 114);
}

h1 {
  /*Afecta a todos los titulos h1*/
  font-size: 4.5vw;
  font-weight: bold;
  vertical-align: middle;
  color: rgb(31, 62, 114);
}

p {
  /*afecta a todos los parrafos P*/
  font-size: 1.5vw;
  font-weight: 500;
  color: rgb(109, 123, 147);
}

.infocontainer2 {
  /*Contenedor que ocupa todo el ancho de pantalla para poner info y a la enfermera*/
  box-sizing: border-box;
  -webkit-box-sizing: border-box;
  /* background-color: blueviolet;*/
  padding: 5% 9.4% 5% 9.4%; /*arriba, derecha,abajo,izq*/
}
.container-info {
  position: relative;
  width: 100%;
  overflow: hidden;
  /*background-color: #acc454;*/
  padding: 2% 0%;
}
</style>
