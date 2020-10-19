<template>
    <div>
  <b-navbar type="dark" variant="dark">
   <b-navbar variant="faded" type="light">
            <b-navbar-brand href="#">My APP</b-navbar-brand>
        </b-navbar>
   <b-navbar-nav class="ml-auto">
       
      <!-- Navbar dropdowns -->
      <b-container >
      <b-nav-item>
        <router-link to="/">Inicio</router-link>
      </b-nav-item>
       <b-nav-item>
        <router-link to="/">Buscar</router-link>
      </b-nav-item>
       <b-nav-item>
        <router-link to="/">Acerca De</router-link>
      </b-nav-item>
    </b-container>
    
    </b-navbar-nav>
  </b-navbar>
  </div>
</template>



<style scoped>

</style>