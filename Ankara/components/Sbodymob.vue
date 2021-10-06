<template>
    <div class="maxcontain">
        <div id="demo" class="sub__contain">
            <button @click="show = !show" class="show__button">
                Toggle render
            </button>

        <transition name="slide-fade">
            <div v-show="show" class="list__container">
                <li class="li__text"><Nuxt-link to="/estados/Aragua" class="Nuxt">Aragua</Nuxt-link></li>
                    <li class="li__text"><Nuxt-link to="/estados/Anzoategui" class="Nuxt">Anzotegui</Nuxt-link></li>
                    <li class="li__text"><Nuxt-link to="/estados/Barquisimeto" class="Nuxt">Barquisimeto</Nuxt-link></li>
                    <li class="li__text"><Nuxt-link to="/estados/Barinas" class="Nuxt">Barinas</Nuxt-link></li>
                    <li class="li__text"><Nuxt-link to="/estados/Caracas" class="Nuxt">Caracas</Nuxt-link></li>
                    <li class="li__text"><Nuxt-link to="/estados/Falcón" class="Nuxt">Falcón</Nuxt-link></li>
                    <li class="li__text"><Nuxt-link to="/estados/Mérida" class="Nuxt">Mérida</Nuxt-link></li>
                    <li class="li__text"><Nuxt-link to="/estados/Miranda" class="Nuxt">Miranda</Nuxt-link></li>
                    <li class="li__text"><Nuxt-link to="/estados/Monagas" class="Nuxt">Monagas</Nuxt-link></li>
                    <li class="li__text"><Nuxt-link to="/estados/Nueva" class="Nuxt">Nueva Esparta</Nuxt-link></li>
                    <li class="li__text"><Nuxt-link to="/estados/Portuguesa" class="Nuxt">Portuguesa</Nuxt-link></li>
                    <li class="li__text"><Nuxt-link to="/estados/Puerto" class="Nuxt">Puerto Ordaz</Nuxt-link></li>
                    <li class="li__text"><Nuxt-link to="/estados/Sucre" class="Nuxt">Sucre</Nuxt-link></li>
                    <li class="li__text"><Nuxt-link to="/estados/Trujillo" class="Nuxt">Trujillo</Nuxt-link></li>
                    <li class="li__text"><Nuxt-link to="/estados/Valencia" class="Nuxt">Valencia</Nuxt-link></li>
                    <li class="li__text"><Nuxt-link to="/estados/Vargas" class="Nuxt">Vargas</Nuxt-link></li>
                    <li class="li__text z"><Nuxt-link to="/estados/Zulia" class="Nuxt">Zulia</Nuxt-link></li>
            </div>
        </transition>
        </div>
    </div>
</template>

<style>

    .maxcontain{
        width: 100%;
        height: 20vh;
    }

    .sub__contain{
        width: 100%;
        height: 20vh;
    }

    .show__button{
        width: 80%;
        height: 5vh;
    }

    .list__container{
        background-color: grey;
        width: 80%;
        height: 80vh;
    }

    .slide-fade-enter-active {
        transition: all 0.3s ease-out;
    }

    .slide-fade-leave-active {
        transition: all 0.8s cubic-bezier(1, 0.5, 0.8, 1);
    }

    .slide-fade-enter-from,
    .slide-fade-leave-to {
        transform: translateY(20px);
        opacity: 0;
    }

    @media (min-width: 920px) {
        .maxcontain{
            display: none;
        }   
}



</style>

<script>

export default {
    data() {
    return {
      show: false
    }
  }
}
</script>