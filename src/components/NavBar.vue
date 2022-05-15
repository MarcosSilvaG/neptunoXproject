<template>
  <div class="header">
    <nav class="nav">
      <a href="#" class="nav-logo">NeptunoXproject</a>
      <div class="nav-menu" :class="isShow ? 'show' : ''">
        <ul class="nav-list">
          <li class="nav-item">
            <a href="#" class="nav-link"
              ><i class="bx bxs-home nav-icon titulo"></i>Home</a
            >
          </li>
          <li class="nav-item">
            <a href="#infocontainer2" class="nav-link"
              ><i class="bx bxs-award nav-icon titulo"></i>Modelo3D</a
            >
          </li>
        </ul>
        <i class="bx bx-x nav-close" @click="isShow = !isShow"></i>
      </div>
      <div class="nav-toggle" @click="isShow = !isShow">
        <i class="bx bx-menu"></i>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  data() {
    return {
      isShow: false,
    };
  },
};
</script>

<style>
.titulo {
  -webkit-text-stroke: 0.05vw white;
}
.header {
  position: fixed;
  width: 100%;
  margin-bottom: 1rem;
  left: 0;
  top: 0;
  background-color: var(--bg-color);
  text-align: left;
  z-index: 2000;
}
.nav {
  max-width: 1024px;
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
  -webkit-text-stroke: 0.05vw white;
}

@media screen and (max-width: 768px) {
  .nav-menu {
    position: fixed;
    left: 0;
    top: -100%;
    width: 100%;
    background-color: var(--bg-color);
    border-radius: 0.8rem 0.8rem 0 0;
    padding: 3rem 0 4rem;
    font-size: 1.5rem;
    transition: 0.4s;
  }
}
.nav-menu.show {
  top: 0;
}
.nav-list {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  row-gap: 1rem;
}

.nav-link {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  row-gap: 1.5rem;
}

.nav-link:hover {
  color: var(--text-color-alt);
}
.nav-icon {
  font-size: 2.5rem;
}
.nav-close {
  position: absolute;
  top: 15px;
  right: 20px;
  font-size: 3rem;
  color: var(--text-color-alt);
}
.nav-toggle {
  font-size: 3rem;
}

@media screen and (min-width: 769px) {
  .header {
    top: 0;
    bottom: initial;
  }
  .nav {
    height: 90px;
  }
  .nav-logo {
    font-size: 2.2rem;
  }
  .nav-list {
    display: flex;
    column-gap: 1.5rem;
  }
  .nav-toggle,
  .nav-icon,
  .nav-close {
    display: none;
  }
  .nav-item {
    font-size: 1.2rem;
  }
}
</style>
