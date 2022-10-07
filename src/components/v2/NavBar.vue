<template>
<nav class="navbar navbar-expand-lg bg-primary">
    <div class="container-md">
        <img src="../../assets/ELIOS.png" alt="logo" class="img">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
        <li class="nav-item">
            
            <router-link to="/" class="nav-link" aria-current="page" href="#">Inicio</router-link>
        </li>
        <li class="nav-item">
            <router-link to="/hotels" class="nav-link" aria-current="page" href="#">Hoteles</router-link>
        </li>
        <li class="nav-item">
            <router-link to="/rooms" class="nav-link" aria-current="page" href="#">Tipo de Habitaciones</router-link>
        </li>
        </ul>
    </div>
    </div>
</nav>
</template>
<style>
      .img{
    width: 100px;
    height: 45px;
    border-radius: 0.3em;
  }

</style>