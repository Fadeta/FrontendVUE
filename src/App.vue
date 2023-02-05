<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-dark">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img src="./assets/itts-big.png" alt="Logo" width="55" height="70" class="d-inline-block align-text-top">
        </a>
    
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
       </button>

        <div class="collapse navbar-collapse" id="navbarCollapse">
          <ul class="navbar-nav align-items-lg-center align-items-start ml-auto">
            <li class="nav-item">
              <router-link :to="{name: 'home'}" class="nav-link text-white text-bold" aria-current="page">HOME</router-link>
            </li>
            <li class="nav-item">
              <router-link :to="{name: 'views.index'}" class="nav-link text-white text-bold">DAFTAR PINJAMAN</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <!-- render vue router -->
    <router-view></router-view>
  </div>
  
</template>

<script>
  export default {

  }
</script>

<style>
 body {
   background-color: rgb(255, 255, 255) !important;
 }

 .mt-custom {
   margin-top: 110px;
 }
 
</style>