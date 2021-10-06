<template>
    <div>
        <div class="Int__cont C">
            <h1 class="titlee">Casco Central</h1>
        </div>

        <div class="Int__body">
            <div class="Int__sub__cont F">
                <img src="@/static/ANKARA.svg" alt="Logo" class="img">
            </div>

            <div class="Int__sub__cont I">                
                <div class="Int__const">

                    <div class="Int__inside">
                        <img src="@/static/iso_ankara.svg" alt="Logo" class="img">
                    </div>

                    <div class="Int__inside">
                        <img src="@/static/iso_ankara.svg" alt="Logo" class="img">
                    </div>
                
                </div>
                
                <div class="Int__const">

                    <div class="Int__inside">
                        <img src="@/static/iso_ankara.svg" alt="Logo" class="img">
                    </div>

                    <div class="Int__inside">
                        <img src="@/static/iso_ankara.svg" alt="Logo" class="img">
                    </div>
                
                </div>
            </div>
        </div>
        
        <div class="Int__body second">
            <div class="Box">
            <div class="Int__sub__cont Z">
                <div class="first__contain">

                    <div class="inside__first__contain">
                        <h2>Direccion</h2>

                        <p class="txt__descrip s">Av. Boulevard 5 de Julio. Local N°1. Zona Casco Central.</p>
                    </div>

                    <div class="inside__first__contain">
                        <h2>Horario de Atencion</h2>

                        <p class="txt__descrip">08:00 a.m. - 5:30 p.m</p>
                    </div>            
                </div>

                
                <div class="second__contain">
                    <div class="insider__contain">
                        <div class="icon__box">
                            <img src="@/static/carrito.svg" alt="carrito" class="icon">
                        </div>

                        <div class="txt__box">
                            <p class="txt__descrip">Productos de belleza, cuidado personal, maquillaje, accesorios, barbershop, estética peluquería y !mucho mas!</p>
                        </div>
                    </div>
                </div>

                <div class="third__contain">
                    <h2>¿En que podemos ayudarte?</h2>
                    <p>¿Necesita ayuda para encontrar lo que es adecuado para usted? Conéctese con nosotros a travez de.</p>
                    <div class="tlf__box">
                        <div class="box__contain">
                            <img src="@/static/celular.svg" alt="carrito" class="icon">
                        </div>
                        <div class="contain__box">
                            <p> 0424-8174050</p>
                        </div>
                    </div>
                </div>
            </div>
            </div>
            <div class="Int__sub__cont M">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d694.3028976952869!2d-64.68621908757144!3d10.134215120603459!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8c2d72ecacdbf5e1%3A0x4d7f7bd911e24703!2sBlvrd%205%20de%20Julio%2C%20Barcelona%206001%2C%20Anzo%C3%A1tegui!5e0!3m2!1ses!2sve!4v1633439915246!5m2!1ses!2sve" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
            </div>
        </div>
    </div>
</template>

<style>

    .Int__cont{
        width: 100%;
        height: 30vh;
    }

    .Int__body{
        width: 100%;
        height: 70vh;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .second{
        height: 90vh;
    }

    .Int__sub__cont{
        width: 50%;
        height: 100%;
        display: flex;
        flex-direction: column;
    }

    .Int__const{
        width: 100%;
        height: 50%;
        display: flex;
    }

    .Int__inside{
        width: 50%;
        height: 100%;
        }

    .img{
        width: 100%;
        height: 100%;
    }

    .first__contain{
        border-bottom: 1px solid #f9bab4;
        width: 100%;
        height: 33%;
        display: flex;
        font-family: 'Lato', sans-serif;
        font-size: 30px;
        text-align: center;
    }

    .inside__first__contain{
        width: 50%;
        height: 100%;
    }

    .txt__descrip{
        font-size: 20px;
        text-align: center;
    }

    .s{
        text-align: left;
        padding-left: 1em;
    }

    .second__contain{
        border-bottom: 1px solid #f9bab4;
        width: 100%;
        height: 33%;
        font-family: 'Lato', sans-serif;
        font-size: 20px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .insider__contain{
        display: flex;
        justify-content: flex-start;
        align-items: flex-start;
    }

    .icon__box{
        width: 15%;
        height: 100%;
        display: flex;
        justify-content: flex-end;
    }

    .icon{
        width: 1.5em;
    }

    .third__contain{
        width: 100%;
        height: 34%;
        font-family: 'Lato', sans-serif;
        text-align: center;
        font-size: 20px;
    }

    .tlf__box{
        width: 100%;
        height: 25%;
        display: flex;
        justify-content: center;
    }

    .box__contain{
        width: 5%;
        height: 100%;
    }

    .contain__box{
        width: 22%;
        height: 100%;
        display: flex;
        align-items: center;
    }

    .titlee{
        font-family: photo;
        color: #f6968e;
    }

    .Z{
        width: 95%;
    }

    .C{
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .Box{
        width: 50%;
        height: 95%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    @media (max-width: 920px) {
        
        .I{
            display: none;
        }
        
        .F{
            width: 100%;
        }

        .second{
            display: flex;
            flex-direction: column;
            height: 200vh;
        }

        .Box{
            width: 100%;
        }

        .contain__box{
            width: 30%;
        }
        
        .box__contain{
            width: 8%;
        }
        
        .M{
            width: 100%;
        }
    }
</style>