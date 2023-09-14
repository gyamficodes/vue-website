<template>
  <div id="app">
     <MobileNav :name="name" :menu="menu" :close="close"/>
    <nav>
      <router-link to="/"></router-link> 
      <router-link to="/about"></router-link>
    </nav>
    <router-view/>
  </div>
</template>
<script>
import MobileNav from './components/MobileNav.vue';
export default {
  components:{
    MobileNav
  },
  data(){
  return{
    name: 'Techno',
    menu: 'menu',
    close: 'close',
  }
  },
  methods:{},
  mounted(){}

}

</script>

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
