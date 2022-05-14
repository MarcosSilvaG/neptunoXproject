<template>
  <div class="infocontainer">
    <!--Contenedor completo -->
    <div class="containerinfo1">
      <!---Contenedor de la informacion izq, primer recuadro-->
      <h1>Fight Virus<br />With Vaccines<br /></h1>

      <p>
        Let's stop this pandemic by killing the virus<br />
        with a vaccine, don't let yourself and your<br />
        family get infected
      </p>
    </div>
    <!--Termina contenedor infocontainer-->

    <div class="imgcontainer-enfermera">
      <!--Contenedor de la img -->
    </div>
    <!--Termina contenedor img -->
  </div>
  <!--Termina infocontainer-->
</template>

<script>
export default {
  name: "ContainerDer",
  props: {
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

.infocontainer {
  /*Contenedor que ocupa todo el ancho de pantalla para imagen*/
  box-sizing: border-box;
  -webkit-box-sizing: border-box;
  align-items: center;
  background-color: aqua;
}
.containerinfo1 {
  position: relative;
  align-items: center;
  float: left;
  height: 65.9vw;
  width: 51%;
  overflow: hidden;
  background-color: rgb(255, 0, 0);
  padding: 9.5% 8.5%;
}
.containerinfo1 .icon1 {
  width: 3%;
}

.imgcontainer-enfermera {
  position: relative;
  float: right;
  width: 49%;
  height: 65.9vw;
  overflow: hidden;
  background-color: rgb(111, 0, 255);
  transform: translate(0%, 0%);
}
.imgcontainer-enfermera img {
  width: 100%;
  height: 100%;
}
</style>
