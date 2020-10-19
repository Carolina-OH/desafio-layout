<template>
  <div id="app">
    <div id="nav">
    <navbar></navbar>
    <gallery></gallery>

    </div>
    
  </div>
</template>

<script>
import navbar from './components/navbar.vue';
import gallery from './components/gallery.vue'
export default {
  name: 'component-name',
  // props: {},
  data: function(){
    return {}
  },
  // computed: {},
  methods: {
    // -- Metodos
  },
  components: {
    'navbar':navbar,
    'gallery':gallery
  },
}
</script>

<style scoped>
  
</style>
<style>
body{
  margin:0;
  padding:0;

}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 0px;
}

#nav a {
  font-weight: bold;
  color: white;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
