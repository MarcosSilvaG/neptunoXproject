<template>
  <div class="infocontainer2">
    <!--Apartado donde sale la informacion "Why should i vaccine?-->
    <div class="container-info">
      <h1>{{ titulo }}</h1>
    </div>
    <div class="container-info">
      <p>
        {{ descripcion }}
      </p>
    </div>
    <div class="container-info">
      <div class="minicontainer">
        <img src="../assets/icons/trash.png" />
        <h3>Recogiendo los desechos</h3>
      </div>
      <div class="minicontainer">
        <img src="../assets/icons/bottlerecycle.png" />
        <h3>Reciclando los plasticos</h3>
      </div>
      <div class="minicontainer">
        <img src="../assets/icons/3dprint.png" />
        <h3>Un poco de creatividad y una impresora 3D</h3>
      </div>
      <div class="minicontainer">
        <img src="../assets/icons/turtleicon.png" />
        <h3>Protesis para especies marinas funcionales</h3>
      </div>
    </div>
  </div>
  <!--Termina why should i vaccines-->
</template>

<script>
export default {
  name: "RecycleContainer",
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
.minicontainer {
  position: relative;
  align-items: center;
  margin-left: 2%;
  margin-right: 2%;
  padding: 2% 2%;
  float: left;
  height: 14.5vw;
  width: 21%;
  overflow: hidden;
  background-color: white;
  border: 0.3vw solid rgb(245, 248, 253);
  border-radius: 1vw;
}
.minicontainer img {
  width: 4vw;
}
.minicontainer h3 {
  font-size: 1.5vw;
  vertical-align: middle;
  color: rgb(31, 62, 114);
}
.minicontainer p {
  font-size: 1vw;
  position: relative;
  top: 1vw;
  color: rgb(109, 123, 147);
}
.infocontainer2 {
  /*Contenedor que ocupa todo el ancho de pantalla para poner info y a la enfermera*/
  box-sizing: border-box;
  -webkit-box-sizing: border-box;
  background-color: blueviolet;
  padding: 5% 9.4% 5% 9.4%; /*arriba, derecha,abajo,izq*/
}
.container-info {
  position: relative;
  width: 100%;
  overflow: hidden;
  background-color: #acc454;
  padding: 2% 0%;
}
</style>
