<template>
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <h1>Baño Destacados</h1>
          <div class="row">
            <div class="col-md-4" v-for="product in products" :key="product.id">
              <AppProducto
                :image="product.image"
                :title="product.title"
                :description="product.description"
                :price="product.price"
              />
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <img src="../assets/banner.png" alt="Imagen" class="img-fluid image-right">
        </div>
      </div>
    </div>
  </template>
  
  
  <script>
  import AppProducto from './AppProducto.vue';
  
  export default {
    components: {
      AppProducto
    },
    data() {
      return {
        products: [
          {
            id: 1,
            image: require('@/assets/Griferia1.jpg'),
            title: 'Producto 1',
            description: 'Descripción del producto 1',
            price: '$19.99'
          },
          {
            id: 2,
            image: require('@/assets/Griferia1.jpg'),
            title: 'Producto 2',
            description: 'Descripción del producto 2',
            price: '$29.99'
          },
          {
            id: 3,
            image: require('@/assets/Griferia1.jpg'),
            title: 'Producto 3',
            description: 'Descripción del producto 3',
            price: '$39.99'
          }
        ]
      };
    }
  };
  </script>

<style>
.image-right {
    position: absolute;
    right: 30px;
}


</style>
  