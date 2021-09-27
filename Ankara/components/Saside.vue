<template>
    <div class="container__father">
        <div class="container__aside">
            <nav>
                <ul class="container__ul menu">
                    <li class="li__title">Estados</li>
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
                </ul>
            </nav>
        </div>
    </div>
</template>

<style>

    .container__father{
        width: 25%;
        height: 140vh;
        display: flex;
        justify-content: center;
        align-items: center;

    }

    .container__aside{
        width: 80%;
        height: 125vh;
        border-radius: 20px;

    }

    .container__ul{
        list-style: none;
        padding-left: 0;
        -webkit-box-shadow: 0px 10px 13px -7px #000000, 5px 5px 17px 1px rgba(0,0,0,0); 
        box-shadow: 0px 10px 13px -7px #000000, 5px 5px 17px 1px rgba(0,0,0,0);
        border-top-right-radius: 20px;
        border-top-left-radius: 20px;
        border-bottom-right-radius: 20px;
        border-bottom-left-radius: 20px;
    }

    .li__title{
        width: 100%;
        height: 7vh;
        font-family: 'Lato', sans-serif;
        font-size: 30px;
        font-weight: bold;
        border-top-right-radius: 20px;
        border-top-left-radius: 20px;
        text-align: center;
        background-color: #f6968e;
        color: white;
    }

    .li__text{
        border-bottom: 1px solid #9c9c9c;
        width: 100%;
        height: 7vh;
        font-family: 'Lato', sans-serif;
        font-weight: 700;
        font-size: 18px;
        padding-left: 1em;
        padding-top: 0.5em;
        background-color: white;
        transition: border-bottom .4s;
        color: #111;
    }

    .Nuxt{
        text-decoration: none !important;
        color: #111;
    }

    .Nuxt:hover{
        color: black;
    }

    .Nuxt:hover{
        border-bottom: none;
    }

    .li__text:hover{
        border-bottom: 1px solid #f6968e;
    }

    .z{
        border-bottom: none;
        border-bottom-right-radius: 20px;
        border-bottom-left-radius: 20px;
    }

    .button{
        display: none;
    }

    @media (max-width: 920px) {
    .container__father{
        display: none;
    }


}

</style>