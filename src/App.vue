<template>

<navbarComp/>
<div>
  <router-view/>
</div>
<footerComp/>

</template>

<script>
import navbarComp from './components/navbarComp.vue'
import footerComp from './components/footerComp.vue'

export default{
  components:{
    navbarComp,
    footerComp
  }
}
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>



