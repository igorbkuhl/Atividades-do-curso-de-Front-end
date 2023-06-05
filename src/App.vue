<template>
  <nav>
    <router-link to="/">Página inicial</router-link> |
    <router-link to="/about">Sobre</router-link>
  </nav>
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

body {
  background-color: #2c3e50;
  color: #f5b3df;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #f5b3df;
}

nav a.router-link-exact-active {
  color: #b94279;
}
</style>
