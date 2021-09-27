<template>
    <div>
        <head>
        <link
        rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
        />
        </head>

        <div class="container a">
            <img src="@/static/carrusel_1.png" class="img" >
        </div>
        <div class="container s">
            <img src="@/static/carrusel_2.png" class="img" >
        </div>
        <div class="container t">
            <img src="@/static/carrusel_3.png" class="img" >
        </div>
        
    </div>
</template>

<style scoped>
@media (min-width: 920px) {
  div{
    display: none;
  }
}

div{
    max-width: 100%;
}

.img{
    width: 80%;
    border-radius: 2em;
}

@keyframes Transport {
    0%{
        transform: translateX(0);
    }
    35%{
        transform: translateX(15%);
    }
    65%{
        transform: translateX(-16%);
    }
    100%{
        transform: translateX(0);
    }
}

@keyframes Transport-a {
    0%{
        transform: translateX(0);
    }
    35%{
        transform: translateX(-7.5%);
    }
    65%{
        transform: translateX(25%);
    }
    100%{
        transform: translateX(0);
    }
}

@keyframes Transport-b {
    0%{
        transform: translateX(0);
    }
    35%{
        transform: translateX(-25%);
    }
    65%{
        transform: translateX(6%);
    }
    100%{
        transform: translateX(0);
    }
}

.a{
    animation-name: Transport-a;
    animation-duration: 2.5s;
    padding-top: 1em;
}

.s{
    display: flex;
    justify-content: center;
    animation-name: Transport;
    animation-duration: 2.5s;
}

.t{
    display: flex;
    justify-content: flex-end;
    animation-name: Transport-b;
    animation-duration: 2.5s;
}
</style>