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
  padding: 5% 0% 5% 0%; /*arriba, derecha,abajo,izq*/
}
.infocontainer3 img {
  width: 44.6%;
  height: 45vw;
}
.infocontainer3 .container {
  position: relative;
  align-items: center;
  padding: 0% 10% 0% 5%;
  float: right;
  height: 45vw;
  width: 55.4%;
  overflow: hidden;
  /*background-color: rgba(255, 0, 0,0.5);*/
}
.infocontainer3 .container2 {
  position: relative;
  align-items: center;
  float: left;
  padding: 0% 8% 0% 9.5%;
  height: 55vw;
  width: 55.4%;
  overflow: hidden;
  /*background-color: rgba(255, 0, 0,0.5);*/
}
.infocontainer3 .container2 .pseparador {
  margin-bottom: 5vw;
}
.infocontainer3 .markcontainer {
  position: relative;
  padding: 10% 10% 10% 7%;
  height: 45vw;
  width: 100%;
  overflow: hidden;
  /*background-color: rgb(255, 0, 140);*/
  text-align: left;
}

.infocontainer3 h3 {
  padding-top: 1vw;
  padding-bottom: 2.5vw;
  font-size: 1.2vw;
}
</style>
