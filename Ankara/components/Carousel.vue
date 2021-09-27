<template>
    <div>
  <b-carousel
    id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    img-width="1024"
    img-height="480"
  >
    <b-carousel-slide
      caption=""
      img-src="@/static/carrusel_1.png"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="@/static/carrusel_2.png"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="@/static/carrusel_3.png"
    ></b-carousel-slide>
  </b-carousel>
</div>
</template>

<style scoped>
@media (max-width: 920px) {
  div{
    display: none;
  }
}
</style>