<template>
  <div class="infocontainer3">
    <!--Apartado donde sale la informacion "prepare before vaccine"-->
    <img src="../assets/turtlehunt.jpg" />
    <div class="container">
      <h1>{{ titulo }}</h1>
      <p>
        {{ descripcion }}
      </p>
    </div>
    <!---->
  </div>
  <!--Termina prepare vaccines-->
</template>

<script>
export default {
  name: "ContainerIzq",
  props: {
    titulo: String,
    descripcion: String,
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

.infocontainer3 {
  /*Contenedor que ocupa todo el ancho de pantalla para poner info y a la enfermera*/
  box-sizing: border-box;
  -webkit-box-sizing: border-box;
  /*background-color: rgb(107, 255, 38);*/
  padding: 5% 0% 0% 0%; /*arriba, derecha,abajo,izq*/
}
.infocontainer3 img {
  width: 44.6%;
  height: 30vw;
}
.infocontainer3 .container {
  position: relative;
  align-items: center;
  padding: 2.5% 10% 2.5% 5%;
  float: right;
  height: 30vw;
  width: 55.4%;
  overflow: hidden;
  background-size: 100% 100%;
  background-repeat: no-repeat;
  background: url("../assets/background/sea2.png");
  background-size: cover;
  /*background-color: rgba(255, 0, 0, 0.5);*/
}
</style>
