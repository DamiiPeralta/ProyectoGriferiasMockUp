<template>
  <div class="app-header">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container app-header">
        <a class="navbar-brand" href="#">
          <img class="logo" src="../assets/logoGgrifos.jpg" alt="Logo">
        </a>
        <form class="d-flex ms-auto">
          <input class="form-control me-2" type="search" placeholder="Buscar" aria-label="Search">
          <button class="btn btn-outline-primary me-2 fontwhite" type="submit">Buscar</button>
        </form>
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="#"><i class="bi bi-cart-fill"></i></a>
          </li>
          <li class="nav-item">
            <a class="nav-link ms-2 fontwhite" href="#">Ingresar</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'AppHeader',
  props: {
    msg: String
  }
}
</script>

<style>
.app-header {
  background-color: black;
}

.logo {
  height: 100%;
  width: auto;
}

.navbar-nav .fontwhite {
  color: white;
}
</style>

