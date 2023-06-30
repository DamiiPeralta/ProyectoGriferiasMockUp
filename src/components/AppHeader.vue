<template>
    <div>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#"><img src="../assets/logo.jpg" alt="Logo" width="50"></a>
      <form class="d-flex ms-auto">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-primary me-2" type="submit">Search</button>
      </form>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#"><i class="bi bi-cart-fill"></i></a>
        </li>
        <li class="nav-item">
          <a class="nav-link ms-2" href="#">Login</a>
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
  
  <style scoped>
  
  </style>