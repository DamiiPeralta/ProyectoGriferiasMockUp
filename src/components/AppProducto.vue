<template>
    <div class="product-card card">
      <img :src="image" alt="Product Image" class="card-img-top">
      <div class="card-body d-flex flex-column align-items-center">
        <h5 class="card-title">{{ title }}</h5>
        <p class="card-text">{{ description }}</p>
        <p class="card-text">{{ price }}</p>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      image: {
        type: String,
        required: true
      },
      title: {
        type: String,
        required: true
      },
      description: {
        type: String,
        required: true
      },
      price: {
        type: String,
        required: true
      }
    }
  };
  </script>
  
  <style scoped>
.product-card {
  width: 100%;
  margin-bottom: 20px;
}

.card-img-top {
  max-height: 100%;
}
</style>
  
  