<template>
  <div id="app">
    <nav>
      <router-link to="/"></router-link> 
      <router-link to="/about"></router-link>
    </nav>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

nav {


  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
@import'./assets/Sass/Style.scss';
</style>
