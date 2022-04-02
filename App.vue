<template>
  <nav>
    <router-link to="/">Inicio</router-link> |
    <router-link to="/pedido">Pedido</router-link> |
    <router-link to="/pastelero">Pastelero</router-link>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: rgb(73, 213, 248);
  background-color: rgb(107, 243, 253);
}

nav {
  padding: 30px;
  background-color:rgb(207, 253, 255) ;
  text-align: left;
}

nav a {
  font-weight: bold;
  color: rgb(73, 213, 248);
}

nav a.router-link-exact-active {
  color: rgb(73, 213, 248);
}

</style>