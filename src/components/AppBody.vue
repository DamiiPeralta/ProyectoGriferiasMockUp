<template>
    <div>
        <AppCarrousel1></AppCarrousel1>
        <AppBanner></AppBanner>
        <AppDescuentos></AppDescuentos>
        <AppDescuentos2></AppDescuentos2>
        <AppCarrousel1></AppCarrousel1>
        <h1>Baño</h1>
        <AppProductList></AppProductList>
        
          <h1>Cocina</h1>
        <div class="background-change">
          <h1 class="font-white">Linea Aleggra</h1>
          <AppProductList></AppProductList>
        </div>
          <h1>Linea Estrella</h1>
          <AppProductList></AppProductList>
        <div class="background-change">
          <h1 class="font-white">Linea Marea</h1>
          <AppProductList></AppProductList>
        </div>
          <h1>Combo Vanitory</h1>
          <AppProductList></AppProductList>
        
        
        
        

    </div>
      
  </template>
  
  <script>

  import AppCarrousel1 from './AppCarrousel1.vue';
  import AppBanner from './AppBanner.vue';
  import AppDescuentos from './AppDescuentos.vue';
  import AppDescuentos2 from './AppDescuentos2.vue';
  import AppProductList from './AppProductList.vue'

  export default {
    name: 'AppBody',
    props: {
      msg: String
    },
    components: {
    AppCarrousel1,
    AppBanner,
    AppDescuentos,
    AppDescuentos2,
    AppProductList
  }
  }
  </script>
  
  <style scoped>
  .background-change {
    background-color: black;
  }
  .font-white {
    color:white;
  }
  </style>