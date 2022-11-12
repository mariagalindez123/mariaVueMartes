<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link> | 

      <router-link to="/about">About</router-link>|

      <router-link to="/ArchivosView">Archivos</router-link>|

      <router-link to="/VistaView">Vista</router-link>|
    
    
    </nav>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: purple;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
