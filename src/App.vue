<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>
    <div class="nav-fr">
      <div class="logo">
        A/F
      </div>
      <a class="menu-button">
        <svg xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512"><title>Grid</title><rect x="48" y="48" width="176" height="176" rx="20" ry="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/><rect x="288" y="48" width="176" height="176" rx="20" ry="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/><rect x="48" y="288" width="176" height="176" rx="20" ry="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/><rect x="288" y="288" width="176" height="176" rx="20" ry="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/></svg>
      </a>
    </div>

    <div class="wrapper">

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/anotherone">Another one</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style>

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
  position: relative;
  /* font-weight: normal; */
}

header {
  width: 99vw;
}

nav {
  display: flex;
  justify-content: space-around;
  position: absolute;
  height: 5vh;
  width: 100vw;
  z-index: 10;
  font-size: 1.5rem;


  top: 2rem;
  padding: 3rem;
  display: none;
}

.nav-fr {
  height: 5vh;
  position: absolute;
  width: 99vw;
  top: 2rem;
  display: flex;
  align-items: center;
}

.menu-button {
  position: absolute;
  right: 2rem;
  width: 2rem;
  height: 2rem;
  color: rgb(40, 40, 40);
  cursor: pointer;
  display: grid;
  place-items: center;
}

.ionicon {
  width: 100%;
  height: 100%;
  color: black;
  z-index: 2;
}

.logo {
  position: absolute;
  left: 2rem;
  color: rgb(40, 40, 40);
  font-size: 1.5rem;
  font-weight: 700;
}
</style>