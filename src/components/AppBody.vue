<template>
    <div>
        <AppCarrousel1></AppCarrousel1>
        <AppBanner></AppBanner>
        <AppDescuentos></AppDescuentos>

    </div>
      
  </template>
  
  <script>

  import AppCarrousel1 from './AppCarrousel1.vue';
  import AppBanner from './AppBanner.vue';
  import AppDescuentos from './AppDescuentos.vue';

  export default {
    name: 'AppBody',
    props: {
      msg: String
    },
    components: {
    AppCarrousel1,
    AppBanner,
    AppDescuentos,
}
  }
  </script>
  
  <style scoped>
  
  </style>