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
      <img src="../assets/neptunox2.png" class="img" />
    </div>
  </div>
  <!--Termina why should i vaccines-->
</template>

<script>
export default {
  name: "ContainerModel",
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
}

.infocontainer2 {
  /*Contenedor que ocupa todo el ancho de pantalla para poner info y a la enfermera*/
  box-sizing: border-box;
  -webkit-box-sizing: border-box;
  /*background-color: blueviolet;*/
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
