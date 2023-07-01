<template>
    <div class="product-list">
      <div class="row">
        <div class="col-sm-6 col-md-4 col-lg-3" v-for="product in products" :key="product.id">
          <div class ="product-card ">
            <AppProducto
            :image="product.image"
            :title="product.title"
            :description="product.description"
            :price="product.price"
          />
          </div>
            
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
          },
          {
            id: 1,
            image: require('@/assets/Griferia1.jpg'),
            title: 'Producto 1',
            description: 'Descripción del producto 1',
            price: '$19.99'
          }
        
        ]
      };
    }
  };
  </script>
  
  <style scoped>
  .product-list {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }
  .product-card {
  padding: 10px;
 }
  </style>
  