<template>
    <div class="body__container">
        <div class="container__card">
            <div class="card__contain">
                <div class="contain__photo">
                    <img src="@/static/ANKARA.svg" alt="logo ankara">
                </div>
                <div class="contain__txt">
                    <h1 class="txt__title">Edificio Los Hermanos</h1>

                    <h2 class="txt__subtitle">Caracas</h2>

                    <p>Av. ppal. de Los Cortijos entre 3ra transversal y autopista edificio Los Hermanos piso 1.</p>

                    <button class="button__card">Visitar Tienda</button>
                </div>
            </div>

            <div class="card__contain">
                <div class="contain__photo">
                    <img src="@/static/ANKARA.svg" alt="logo ankara">
                </div>
                <div class="contain__txt">
                    <h1 class="txt__title">Edificio Los Hermanos</h1>

                    <h2 class="txt__subtitle">Caracas</h2>

                    <p>Av. ppal. de Los Cortijos entre 3ra transversal y autopista edificio Los Hermanos piso 1.</p>

                    <button class="button__card">Visitar Tienda</button>
                </div>
            </div>

            <div class="card__contain">
                <div class="contain__photo">
                    <img src="@/static/ANKARA.svg" alt="logo ankara">
                </div>
                <div class="contain__txt">
                    <h1 class="txt__title">Edificio Los Hermanos</h1>

                    <h2 class="txt__subtitle">Caracas</h2>

                    <p>Av. ppal. de Los Cortijos entre 3ra transversal y autopista edificio Los Hermanos piso 1.</p>

                    <button class="button__card">Visitar Tienda</button>
                </div>
            </div>

            <div class="card__contain">
                <div class="contain__photo">
                    <img src="@/static/ANKARA.svg" alt="logo ankara">
                </div>
                <div class="contain__txt">
                    <h1 class="txt__title">Edificio Los Hermanos</h1>

                    <h2 class="txt__subtitle">Caracas</h2>

                    <p>Av. ppal. de Los Cortijos entre 3ra transversal y autopista edificio Los Hermanos piso 1.</p>

                    <button class="button__card">Visitar Tienda</button>
                </div>
            </div>
        </div>
    </div>
</template>

<style>

    .body__container{
        width: 75%;
        height: 140vh;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .container__card{
        width: 80%;
        height: 126vh;
        display: flex;
        flex-direction: column;
    }

    .card__contain{
        width: 100%;
        height: 24%;
        margin-top: 0.5em;
        border-radius: 20px;
        display: flex;
        justify-content: center;
        align-items: center;
        box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.08);
        -webkit-box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.08);
        -moz-box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.08);
    }

    .contain__photo{
        width: 35%;
        border-top-left-radius: 20px;
        border-bottom-left-radius: 20px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .contain__txt{
    width: 70%;
    height: 95%;  
    display: flex;
    justify-content: space-between;
    flex-direction: column;
    padding-left: 1.5em;
    font-family: 'Lato', sans-serif;
    }

    .button__card{
        width: 30%;
        height: 100%;
        border-radius: 20px; 
    }

    @media (max-width: 920px) {
        
        .contain__txt{
        width: 70%;
        height: 100%;  
        display: flex;
        justify-content: center;
        flex-direction: column;
        padding-left: 1.5em;
        font-family: 'Lato', sans-serif;
        }

        .txt__title{
            font-size: 22px;
        }

        .txt__subtitle{
            font-size: 20px;
        }

        .body__container{
            width: 100%;
        }

        .button__card{
            width: 50%;
        }
    }
</style>