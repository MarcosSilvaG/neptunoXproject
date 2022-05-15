<template>
  <div class="infocontainer">
    <!--Contenedor completo -->
    <div class="containerinfo1">
      <!---Contenedor de la informacion izq, primer recuadro-->
      <h1>{{ titulo }}</h1>

      <p>
        {{ msg }}
      </p>
    </div>
    <!--Termina contenedor infocontainer-->

    <div class="imgcontainer">
      <img src="../assets/waterpollution.jpg" class="img" />
      <!--Contenedor de la img de enfermera-->
    </div>
    <!--Termina contenedor img -->
  </div>
  <!--Termina infocontainer-->
</template>

<script>
export default {
  name: "ContainerDer",
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

.infocontainer {
  /*Contenedor que ocupa todo el ancho de pantalla para imagen*/
  box-sizing: border-box;
  -webkit-box-sizing: border-box;
  align-items: center;
  /*background-color: aqua;*/
}
.containerinfo1 {
  position: relative;
  align-items: center;
  float: left;
  height: 30vw;
  width: 51%;
  overflow: hidden;
  /*background-color: rgb(255, 0, 0);*/
  padding: 2.5% 8.5%;
}
.containerinfo1 .icon1 {
  width: 3%;
}

.imgcontainer {
  /*Contenedor de imagen*/
  position: relative;
  float: right;
  width: 49%;
  height: 30vw;
  overflow: hidden;
  /*background-color: rgb(111, 0, 255);*/
  transform: translate(0%, 0%);
}
.imgcontainer img {
  width: 100%;
  height: 100%;
}
</style>
