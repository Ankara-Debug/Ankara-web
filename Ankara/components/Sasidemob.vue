<template>
    <div class="maxcontain">
        <div id="demo">
            <button @click="show = !show">
                Toggle render
            </button>

        <transition name="slide-fade">
            <div v-show="show">
                <h1>Hello</h1>
                <h2>como estas</h2>
            </div>
        </transition>
        </div>
    </div>
</template>

<style>

    .maxcontain{
        border: 1px solid black;
        width: 100%;
        height: 20vh;
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