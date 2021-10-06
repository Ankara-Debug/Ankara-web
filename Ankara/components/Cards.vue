<template>
    <div>
        <head>
            <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous"/>
        </head>
        <section class="cont">
        <div class="contenedor">
            <div class="card a">
                <div class="card-encabezado">
                    
                </div>
                <div class="card-iconos">
                    <li class="agrandar"><a href="https://www.instagram.com/ankaraformeve/?hl=es-la"><span class="fab fa-instagram"></span></a></li>    
                </div>
                <div class="card-contenido">
                    <div class="info-personal desplazar title">Ankara For Me </div>
                    <div class="info-personal desplazar"></div>
                    <div class="info-personal desplazar">
                        <p>
                            Siéntete en confianza, segura y con mucha actitud en nuestro <br>
                            espacio exclusivo, donde nuestros profesionales te brindarán <br>
                            la mejor atención y calidad en cada uno de nuestros servicios.
                        </p>
                    </div>
                </div>
            </div>

            <div class="card b">
                <div class="card-encabezado">
                    
                </div>
                <div class="card-iconos">
                    <li class="agrandar"><a href="https://www.instagram.com/ankarastudiove/?hl=es-la"><span class="fab fa-instagram"></span></a></li>    
                </div>
                <div class="card-contenido">
                    <div class="info-personal desplazar title">Ankara Studio</div>
                    <div class="info-personal desplazar"></div>
                    <div class="info-personal desplazar">
                        <p>
                            te brindamosla luz del conocimiento donde podras formarte<br>
                            como maquilladora/o profesional, con capacitadores de <br>
                            calidad que potenciaran tu aprendizaje en el mundo de <br>
                            la belleza.
                        </p>
                    </div>
                </div>
            </div>
        </div>
        </section>
    </div>
</template>

<style scoped>

.title{
    font-family: 'Lato', sans-serif;
    font-weight: bold;
    font-size: 20px;
}

.cont{
    padding: 3.125em;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    font-family: 'Lato', sans-serif;
}

.contenedor{
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    max-width: 100%;
    gap: 1em;
    margin: auto;
    justify-items: center;
    align-items: center;
    font-weight: 700;
}

.card{
    height: 16em;
    width: 35em;
    overflow: hidden;
    margin: auto;
    padding: 10px 30px;
    border-radius: 10%;
    border: 1px solid #fff;
    transition: all .4s ease-in-out;
    box-shadow: 0px 1px 5px 0px rgba(0,0,0,0.3);
    text-align: center;
}

.a{
    background: url(@/static/card_as.png);
    background-repeat: no-repeat;
}

.b{
    background: url(@/static/card_ak.png);
    background-repeat: no-repeat;
}

.card:hover{
    height: 31.25em;
    border-radius: 5px;
    box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.5);
}

.card-encabezado {
    position: relative;
    display: block;
    object-fit: cover;
    margin: 20px auto;
    transition: all 0.3s ease;
    padding-top: 12em;
}

.card-iconos{
    display: flex;
    justify-content: center;
    position: relative;
    margin-bottom: 15px;
    list-style: none;
    padding-top: 2em;
    padding-bottom: 3em;
}

.card-iconos li{
    border-radius: 50%;
    background-color: #fff;
    height: 40px;
    width: 40px;
    margin: 0 5px;
    line-height: 40px;
    text-align: center;
    transform: scale(0);
    transform: all 0.5s ease;
}

.desplazar{
    opacity: 0;
    transition: all .5s ease;
    transform: translateY(-45px); 
}

.agrandar{
    transform: scale(0);
    opacity: 0;
    transition: all ,4s ease;
}

.card:hover .agrandar{
    opacity: 1;
    transform: scale(1);
}

.card:hover .desplazar{
    transform: scaleY(0px);
    opacity: 1;
}

.card-iconos li a{
    color: #7813d6;
    height: 100%;
    width: 100%;
    border-radius: 50%;
    background: #fff;
    display: block;
    line-height: 40px;
    transition: all 0.3s;
}
.card-iconos li a:hover{
    transform: scale(1.1);
    box-shadow: 0 0 5px #781378;
}


@media  screen and (max-width: 920px){
    
    .contenedor{
        grid-template-columns: 1fr;
        max-width: 25em;
    }
    .card{
        width: 100%;
    }

    .card-encabezado img{
        padding-top: 1em;
        margin-top: 4.5em;
    }

    .cont{
        height: 60em;
    }
    
    .card-contenido{
        margin-top: -1em;
    }
}




</style>