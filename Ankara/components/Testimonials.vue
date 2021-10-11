<template>
  <div class="container">
    <div class="sub__container">
      <div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      background="#ababab"
      img-width="1024"
      img-height="480"
      
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <!-- Text slides with image -->
    <b-carousel-slide img-src="https://picsum.photos/1024/480/?image=52">
      <div class="div">
        <h1 class="title">Lo que la gente esta diciendo sobre nosotros</h1>
        <div class="card__container">
          <div class="img__container">
            <img src="@/static/model.jpg" alt="model" class="model">
            <p class="p__text">Luna Chacon <br>
              Usuaria Ankara
            </p>
          </div>
        </div>
        <p class="text-a">"Los felicito los conozco desde sus inicios y de veras admiro
          su expansion porque asi son fuente de empleo para muchas familias
          Venezolanas del 2020 al 2021,mil bendiciones".
        </p>
      </div>
    </b-carousel-slide>

    <b-carousel-slide img-src="https://picsum.photos/1024/480/?image=52">
      <div class="div__1">
        <div class="card__container__d" >
          <div class="img__container">
            <img src="@/static/model.jpg" alt="model" class="model">
            <p class="p__text">Luna Chacon <br>
              Usuaria Ankara
            </p>
          </div>
        </div>
        <div class="space"></div>
        <p class="text__e">"Excelente servicios y atencion al cliente, productos de buena
          calidad, gracias por mantenerme bonita y con buenos precios, de
          verdad son excelentes.".
        </p>
      </div>
    </b-carousel-slide>

    <b-carousel-slide img-src="https://picsum.photos/1024/480/?image=52">
      <div class="div__1">
        <div class="card__container__d">
          <div class="img__container">
            <img src="@/static/model.jpg" alt="model" class="model">
            <p class="p__text">Luna Chacon <br>
              Usuaria Ankara
            </p>
          </div>
        </div>
        <div class="space"></div>
        <p class="text__e" >"Siempre digo que voy por un producto y termino con 10, los amo 
          son mis favoritos y sobre todo la atencion tan espectacular 
          son maravillosos.".
        </p>
      </div>
    </b-carousel-slide>

    </b-carousel>


  </div>
    </div>
  </div>
</template>



<style scoped>
.container{
  max-width: 100%;
  height: 40em;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: 'Lato', sans-serif;
  font-size: 20px;
}

.sub__container{
  width: 80%;
  height: 26em;
}

.card__container{
  width: 100%;
  height: 4em;
  display: flex;
  justify-content: center;
}

.div{
    width: 100%;
    height: 24em;   
}

.model{
  width: 4em;
  height: 4em;
  border-radius: 50%;
  
}

.title{
  padding-bottom: 1em;
  font-weight: bold;
  padding-top: 2.2em;
}

.text-a{
  margin-top: 2em;
}

.img__container{
  display: flex;
  justify-content: space-between;
  align-content: center;
  width: 30%;

}

.p__text{
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}


.c{
  margin-top: 10em;
}

.card__container__d{
  display: flex;
  justify-content: center;  
  padding-top: 2.5em;
}

.text__e{
  margin-bottom: 2em;
}

.div__1{
  width: 100%;
  height: 24em;   
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.space{
  width: 100%;
  height: 1.5em;
}

@media  screen and (max-width: 920px){

  .container{
    width: 100%;
    height: 25em;
    font-family:'Lato', sans-serif;
    font-size: 18px;
    display: flex;
    align-items: center;
  }

  .sub__container{
    width: 100%;
    height: 66%;
  }

  .div{
    width: 100%;
    height: 10.5em;
  }

  .title{
    display: none;
  }

  .p__text{
    width: 100%;
  }

  .img__container{
    width: 60%;
  }

  .div__1{
    width: 100%;
    height: 11em;
  }

  .text-a{
    padding-top: 0em;
    margin-top: -0.5em;
  }

  .model{
    width: 3em;
    height: 3em;
    border-radius: 50%;
  }
}
</style>

<script>
  export default {
    data() {
      return {
        slide: 0,
        sliding: null
      }
    },
    methods: {
      onSlideStart(slide) {
        this.sliding = true
      },
      onSlideEnd(slide) {
        this.sliding = false
      }
    }
  }
</script>