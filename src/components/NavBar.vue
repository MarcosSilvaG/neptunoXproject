<template>
  <div class="header">
    <nav class="nav">
      <a href="#" class="nav-logo">NeptunoXproject</a>
      <div class="nav-menu">
        <ul class="nav-list">
          <li class="nav-item">
            <a href="#" class="nav-link"
              ><i class="bx bxs-home nav-icon"></i>Home</a
            >
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link"
              ><i class="bx bxs-award nav-icon"></i>Modelo3D</a
            >
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link"
              ><i class="bx bxs-check-shield nav-icon"></i>Solución</a
            >
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link"
              ><i class="bx bx-conversation nav-icon"></i>Contacto</a
            >
          </li>
        </ul>
        <i class="bx bx-x"></i>
      </div>
      <div class="nav-toggle">
        <i class="bx bx-menu"></i>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style>
.header {
  width: 100%;
  position: relative;
  margin-bottom: 1em;
  left: 0;
  background-color: var(--bg-color);
  text-align: left;
}
.nav {
  height: 3rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-left: 1rem;
  margin-right: 1rem;
}
.nav-logo {
  font-size: 2rem;
  font-weight: 1000;
  color: var(--text-color-alt);
}
.nav-menu {
  position: relative;
  left: 0;
  bottom: 0;
  width: 100%;
  background-color: var(--bg-color);
  border-radius: 0.4rem 0.4rem 0 0;
  padding: 3rem 0 4rem;
}
</style>
