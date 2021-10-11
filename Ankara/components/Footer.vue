<template>
    <section class="container__Footer">
        <div class="container__logo">
            <img src="@/static/ANKARA.svg" alt="Ankara_logo" class="logo__ankara">
        </div>
        <div class="container__information">
            <div class="container__map">
                <div class="container__img">
                    <div class="map">
                        <a href="https://goo.gl/maps/WgHPsQwVhqqhdQCx5"><img src="@/static/mapa.svg" alt="mapa" class="map__1"></a>
                    </div>
                    <div class="map__text">
                        <p class="direcction__text">
                            Ankara 2018 C.A. J-400149150 <br>
                            Edificio Industrial Los Hermanos <br>
                            Avenida Principal Los Cortijos De Lourdes <br>
                            Caracas.
                        </p>
                    </div>
                </div>
            </div>
            <div class="container__social">
                <div class="container__title">
                    <h2 class="contac">Contacto</h2>
                </div>
                <div class="container__icons">
                    <div class="icon__instagram">
                        <a href="https://www.instagram.com/ankaravenezuela/?hl=es-la"><img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEuMSIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHhtbG5zOnN2Z2pzPSJodHRwOi8vc3ZnanMuY29tL3N2Z2pzIiB3aWR0aD0iNTEyIiBoZWlnaHQ9IjUxMiIgeD0iMCIgeT0iMCIgdmlld0JveD0iMCAwIDE2OS4wNjMgMTY5LjA2MyIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgNTEyIDUxMiIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSIgY2xhc3M9IiI+PGc+CjxnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+Cgk8cGF0aCBkPSJNMTIyLjQwNiwwSDQ2LjY1NEMyMC45MjksMCwwLDIwLjkzLDAsNDYuNjU1djc1Ljc1MmMwLDI1LjcyNiwyMC45MjksNDYuNjU1LDQ2LjY1NCw0Ni42NTVoNzUuNzUyICAgYzI1LjcyNywwLDQ2LjY1Ni0yMC45Myw0Ni42NTYtNDYuNjU1VjQ2LjY1NUMxNjkuMDYzLDIwLjkzLDE0OC4xMzMsMCwxMjIuNDA2LDB6IE0xNTQuMDYzLDEyMi40MDcgICBjMCwxNy40NTUtMTQuMjAxLDMxLjY1NS0zMS42NTYsMzEuNjU1SDQ2LjY1NEMyOS4yLDE1NC4wNjMsMTUsMTM5Ljg2MiwxNSwxMjIuNDA3VjQ2LjY1NUMxNSwyOS4yMDEsMjkuMiwxNSw0Ni42NTQsMTVoNzUuNzUyICAgYzE3LjQ1NSwwLDMxLjY1NiwxNC4yMDEsMzEuNjU2LDMxLjY1NVYxMjIuNDA3eiIgZmlsbD0iI2Y2ODY5ZSIgZGF0YS1vcmlnaW5hbD0iIzAwMDAwMCIgc3R5bGU9IiI+PC9wYXRoPgoJPHBhdGggZD0iTTg0LjUzMSw0MC45N2MtMjQuMDIxLDAtNDMuNTYzLDE5LjU0Mi00My41NjMsNDMuNTYzYzAsMjQuMDIsMTkuNTQyLDQzLjU2MSw0My41NjMsNDMuNTYxczQzLjU2My0xOS41NDEsNDMuNTYzLTQzLjU2MSAgIEMxMjguMDk0LDYwLjUxMiwxMDguNTUyLDQwLjk3LDg0LjUzMSw0MC45N3ogTTg0LjUzMSwxMTMuMDkzYy0xNS43NDksMC0yOC41NjMtMTIuODEyLTI4LjU2My0yOC41NjEgICBjMC0xNS43NSwxMi44MTMtMjguNTYzLDI4LjU2My0yOC41NjNzMjguNTYzLDEyLjgxMywyOC41NjMsMjguNTYzQzExMy4wOTQsMTAwLjI4MSwxMDAuMjgsMTEzLjA5Myw4NC41MzEsMTEzLjA5M3oiIGZpbGw9IiNmNjg2OWUiIGRhdGEtb3JpZ2luYWw9IiMwMDAwMDAiIHN0eWxlPSIiPjwvcGF0aD4KCTxwYXRoIGQ9Ik0xMjkuOTIxLDI4LjI1MWMtMi44OSwwLTUuNzI5LDEuMTctNy43NywzLjIyYy0yLjA1MSwyLjA0LTMuMjMsNC44OC0zLjIzLDcuNzhjMCwyLjg5MSwxLjE4LDUuNzMsMy4yMyw3Ljc4ICAgYzIuMDQsMi4wNCw0Ljg4LDMuMjIsNy43NywzLjIyYzIuOSwwLDUuNzMtMS4xOCw3Ljc4LTMuMjJjMi4wNS0yLjA1LDMuMjItNC44OSwzLjIyLTcuNzhjMC0yLjktMS4xNy01Ljc0LTMuMjItNy43OCAgIEMxMzUuNjYxLDI5LjQyMSwxMzIuODIxLDI4LjI1MSwxMjkuOTIxLDI4LjI1MXoiIGZpbGw9IiNmNjg2OWUiIGRhdGEtb3JpZ2luYWw9IiMwMDAwMDAiIHN0eWxlPSIiPjwvcGF0aD4KPC9nPgo8ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgo8L2c+CjxnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjwvZz4KPGcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPC9nPgo8ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgo8L2c+CjxnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjwvZz4KPGcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPC9nPgo8ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgo8L2c+CjxnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjwvZz4KPGcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPC9nPgo8ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgo8L2c+CjxnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjwvZz4KPGcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPC9nPgo8ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgo8L2c+CjxnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjwvZz4KPGcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPC9nPgo8L2c+PC9zdmc+" class="instagram"/></a>
                    </div>
                    <div class="icon__tiktok">
                        <a href="https://www.tiktok.com/@ankarave?"><img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEuMSIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHhtbG5zOnN2Z2pzPSJodHRwOi8vc3ZnanMuY29tL3N2Z2pzIiB3aWR0aD0iNTEyIiBoZWlnaHQ9IjUxMiIgeD0iMCIgeT0iMCIgdmlld0JveD0iMCAwIDUxMiA1MTIiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDUxMiA1MTIiIHhtbDpzcGFjZT0icHJlc2VydmUiIGNsYXNzPSIiPjxnPjxwYXRoIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgZD0ibTQ3NS4wNzQgMGgtNDM4LjE0OGMtMjAuMzk1IDAtMzYuOTI2IDE2LjUzMS0zNi45MjYgMzYuOTI2djQzOC4xNDhjMCAyMC4zOTUgMTYuNTMxIDM2LjkyNiAzNi45MjYgMzYuOTI2aDQzOC4xNDhjMjAuMzk1IDAgMzYuOTI2LTE2LjUzMSAzNi45MjYtMzYuOTI2di00MzguMTQ4YzAtMjAuMzk1LTE2LjUzMS0zNi45MjYtMzYuOTI2LTM2LjkyNnptLTkwLjgyNyAxOTUuOTU5djM0LjYxM2MtMTYuMzIyLjAwNi0zMi4xODEtMy4xOTItNDcuMTM3LTkuNTAzLTkuNjE3LTQuMDYtMTguNTc3LTkuMjkyLTI2Ljc3Mi0xNS42MTNsLjI0NiAxMDYuNTQyYy0uMTAzIDIzLjk5MS05LjU5NCA0Ni41MzItMjYuNzcyIDYzLjUxLTEzLjk4IDEzLjgyLTMxLjY5NSAyMi42MDktNTAuODk1IDI1LjQ1My00LjUxMi42NjgtOS4xMDMgMS4wMTEtMTMuNzQ2IDEuMDExLTIwLjU1MyAwLTQwLjA2Ny02LjY1OS01Ni4wMjktMTguOTQzLTMuMDA0LTIuMzEzLTUuODc2LTQuODItOC42MTItNy41MjEtMTguNjE3LTE4LjQtMjguMjE3LTQzLjM0LTI2LjYwMS02OS41NzUgMS4yMzQtMTkuOTcxIDkuMjI5LTM5LjAxNyAyMi41NTgtNTMuOTQ1IDE3LjYzNS0xOS43NTQgNDIuMzA2LTMwLjcxOSA2OC42ODQtMzAuNzE5IDQuNjQzIDAgOS4yMzQuMzQ4IDEzLjc0NiAxLjAxN3YxMi43OTggMzUuNjAxYy00LjI3Ny0xLjQxMS04Ljg0Ni0yLjE4Ny0xMy42MDMtMi4xODctMjQuMSAwLTQzLjU5NyAxOS42NjItNDMuMjM3IDQzLjc3OS4yMjggMTUuNDMxIDguNjU4IDI4LjkyIDIxLjA5IDM2LjM1NSA1Ljg0MiAzLjQ5NSAxMi41NjQgNS42NTkgMTkuNzM3IDYuMDUzIDUuNjIuMzA4IDExLjAxNi0uNDc0IDE2LjAxMy0yLjEyNCAxNy4yMTgtNS42ODggMjkuNjM5LTIxLjg2MSAyOS42MzktNDAuOTM1bC4wNTctNzEuMzQ2di0xMzAuMjUyaDQ3LjY2OGMuMDQ2IDQuNzIzLjUyNSA5LjMzMiAxLjQxNiAxMy43OTcgMy41OTggMTguMDc1IDEzLjc4NiAzMy43NTcgMjcuOTY2IDQ0LjQ0OCAxMi4zNjQgOS4zMjYgMjcuNzYgMTQuODU0IDQ0LjQ0OCAxNC44NTQuMDExIDAgLjE0OCAwIC4xMzctLjAxMXYxMi44NDN6IiBmaWxsPSIjZjY5NjhlIiBkYXRhLW9yaWdpbmFsPSIjMDAwMDAwIiBzdHlsZT0iIiBjbGFzcz0iIj48L3BhdGg+PC9nPjwvc3ZnPg==" class="instagram"/></a>
                    </div>
                </div>
            </div>
            <div class="container__navigation">
                <div class="container__list">
                    <h2 class="contac">Navegacion</h2>
                    <nav>
                        <ul class="list">
                            <div class="about__container">
                                <li class="li__txt"><Nuxt-link to="/" class="lnk">Home</Nuxt-link></li>
                                <li><Nuxt-link to="/About" class="lnk">About</Nuxt-link></li>
                            </div>
                            <div class="about__container">
                                <li><Nuxt-link to="/Stores" class="lnk">Stores</Nuxt-link></li>
                                <li><a href="#" class="links">Gallery</a></li>
                            </div>
                        </ul>
                    </nav>
                </div>
            </div>
        </div>
        <div class="copyright">
            <h1 class="copyright__text"> Copyright Ankara 2018 C.A.</h1>
        </div>
    </section>
</template>

<style>

.lnk{
    color: black;
    text-decoration: none !important;;
}

.lnk:hover{
    color: black;
}

.map__1{
    width: 2em;
    margin-left: 6em;
}

.container__Footer{
    width: 100%;
    height: 100%;
    background: linear-gradient(white 60%, #facbc6);
}

.container__logo{
    width: 100%;
    height: 8em;
    padding-left: -2em;
}

.container__information{
    width: 100%;
    height: 8em;
    display: flex;
}


.container__navigation{
    width: 35%;
    height: 100%;

}

.copyright{
    width: 100%;
    height: 5em;
    border-top: 1px solid black;
    display: flex;
    justify-content: center;
    align-items: center;
}

.copyright__text{
    font-family: 'Lato', sans-serif;
    font-size: 20px;
    color: black;
    font-weight: bold;
}

.container__logo{
    display: flex;
    justify-content: flex-start;
    align-content: center;
    border-top: 2px solid #facbc6;
}

.logo__ankara{
    width: 25em;
    padding-left: 5em;
}

.map{
    width: 30%;
    height: 100%;
}

.container__map{
    width: 35%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}

.container__img{
    width: 100%;
    height: 6em;
    display: flex;
}

.text{
    width: 30%;
}

.map__text{
    width: 70%;
    height: 100%;
}

.direcction__text{
    font-family: 'Lato', sans-serif;
    font-weight: 700;
}

.container__tlf{
    width: 100%;
    height: 2em;
    display: flex;
}

.container__social{
    width: 30%;
    height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.container__title{
    width: 100%;
    height: 2em;
    margin-top: 0.5em;
}

.contac{
    text-align: center;
    font-family: 'Lato', sans-serif;
    font-weight: bold;
}

.container__icons{
    width: 24%;
    height: 4em;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 0.5em;
}

.icon__instagram{
    width: 2.5em;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.icon__tiktok{
    width: 2.5em;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.instagram{
    width: 100%;
}

.container__list{
    width: 100%;
    height: 2em;
    margin-top: 0.5em;
    font-family: 'Lato', sans-serif;
    font-weight: 700;
}

.list{
    list-style: none;
    display: flex;
    flex-direction: column;
    text-decoration: none;
}


.about__container{
    display: flex;
    width: 70%;
    height: 1.5em;
    justify-content: space-between;
    margin-left: 3em;
    text-decoration: none;
}

.links{
    text-decoration: none;
    color: black;
}



@media (max-width: 920px) {
    .container__Footer{
        display: none;
    }


}
</style>