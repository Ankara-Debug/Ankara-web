<template>
    <section class="cont__about">
        <div class="cont__text">
            <p class="txt__tittle">Nosotros</p>
        </div>
        <div class="txt__paragraph">
        <p>Ankara nació para superar las expectativas en productos de belleza y cuidado personal, reflejando
            innovación y calidad con presencia más de 20 estados en el territorio venezolano para brindar 
            satisfaccion a todos nuestros clientes
        </p>
        </div>
    </section>
</template>

<style>
    .cont__about{
        height: 100vh;
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }

    .cont__text{
        height: 20vh;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .txt__tittle{
        font-size: 40px;
        font-family: photo;
        color: #f6968e;
    }

    .txt__paragraph{
        width: 80%;
        height: 20vh;
        font-family:'Lato', sans-serif;
        font-weight: 700;
        font-size: 20px;
        text-align: center;
    }
</style>