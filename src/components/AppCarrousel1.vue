<template>
  <div>
    <div id="myCarousel" class="carousel slide" data-bs-ride="carousel">
      <!-- Indicadores del carrusel 
      <ol class="carousel-indicators">
        <li v-for="(slide, index) in slides" :key="index" data-bs-target="#myCarousel" :data-bs-slide-to="index" :class="{ active: index === 0 }"></li>
      </ol>
      -->
      <!-- Slides del carrusel -->
      <div class="carousel-inner">
        <div v-for="(slide, index) in slides" :key="index" class="carousel-item" :class="{ active: index === 0 }">
          <img :src="slide.image" class="d-block w-100" :alt="'Slide ' + (index + 1)">
        </div>
      </div>

      <!-- Controles del carrusel -->
      <a class="carousel-control-prev" href="#myCarousel" role="button" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Anterior</span>
      </a>
      <a class="carousel-control-next" href="#myCarousel" role="button" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Siguiente</span>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      slides: [
        {
          image: require('@/assets/Griferia1.jpg')
        },
        {
          image: require('@/assets/Griferia2.jpg')
        },
        {
          image: require('@/assets/Griferia3.jpg')
        }
      ]
    };
  }
};

</script>

<style>
.carousel-item img {
  height: 300px; /* Ajusta la altura de las imágenes según tus necesidades */
}
</style>
