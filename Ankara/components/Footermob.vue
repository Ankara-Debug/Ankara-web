<template>
    <section class="run">
        <div class="container__Footermob">
            <img src="@/static/ANKARA.svg" alt="Logo Ankara" class="Logo__Ankara">
        </div>
        <div class="container__direction">
            <div class="subcontainer__direction ac">
                <a href="https://goo.gl/maps/WgHPsQwVhqqhdQCx5"><img src="@/static/mapa.svg" alt="mapa" class="mapa"></a>
            </div>
            <div class="subcontainer__direction b">
                <p class="subcontain__text">Ankara 2018 C.A. J-400149150,
                    Edificio Industrial Los Hermanos, 
                    Avenida Principal Los Cortijos De Lourdes,
                    Caracas.</p>
            </div>
        </div>  
        <div class="container__contactmob">
            <h2 class="contac">Contacto</h2>
            <div class="container__iconsmob">
                    <div class="icon__mob">
                        <a href="https://www.instagram.com/ankaravenezuela/?hl=es-la"><img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEuMSIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHhtbG5zOnN2Z2pzPSJodHRwOi8vc3ZnanMuY29tL3N2Z2pzIiB3aWR0aD0iNTEyIiBoZWlnaHQ9IjUxMiIgeD0iMCIgeT0iMCIgdmlld0JveD0iMCAwIDE2OS4wNjMgMTY5LjA2MyIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgNTEyIDUxMiIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSIgY2xhc3M9IiI+PGc+CjxnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+Cgk8cGF0aCBkPSJNMTIyLjQwNiwwSDQ2LjY1NEMyMC45MjksMCwwLDIwLjkzLDAsNDYuNjU1djc1Ljc1MmMwLDI1LjcyNiwyMC45MjksNDYuNjU1LDQ2LjY1NCw0Ni42NTVoNzUuNzUyICAgYzI1LjcyNywwLDQ2LjY1Ni0yMC45Myw0Ni42NTYtNDYuNjU1VjQ2LjY1NUMxNjkuMDYzLDIwLjkzLDE0OC4xMzMsMCwxMjIuNDA2LDB6IE0xNTQuMDYzLDEyMi40MDcgICBjMCwxNy40NTUtMTQuMjAxLDMxLjY1NS0zMS42NTYsMzEuNjU1SDQ2LjY1NEMyOS4yLDE1NC4wNjMsMTUsMTM5Ljg2MiwxNSwxMjIuNDA3VjQ2LjY1NUMxNSwyOS4yMDEsMjkuMiwxNSw0Ni42NTQsMTVoNzUuNzUyICAgYzE3LjQ1NSwwLDMxLjY1NiwxNC4yMDEsMzEuNjU2LDMxLjY1NVYxMjIuNDA3eiIgZmlsbD0iI2Y2ODY5ZSIgZGF0YS1vcmlnaW5hbD0iIzAwMDAwMCIgc3R5bGU9IiI+PC9wYXRoPgoJPHBhdGggZD0iTTg0LjUzMSw0MC45N2MtMjQuMDIxLDAtNDMuNTYzLDE5LjU0Mi00My41NjMsNDMuNTYzYzAsMjQuMDIsMTkuNTQyLDQzLjU2MSw0My41NjMsNDMuNTYxczQzLjU2My0xOS41NDEsNDMuNTYzLTQzLjU2MSAgIEMxMjguMDk0LDYwLjUxMiwxMDguNTUyLDQwLjk3LDg0LjUzMSw0MC45N3ogTTg0LjUzMSwxMTMuMDkzYy0xNS43NDksMC0yOC41NjMtMTIuODEyLTI4LjU2My0yOC41NjEgICBjMC0xNS43NSwxMi44MTMtMjguNTYzLDI4LjU2My0yOC41NjNzMjguNTYzLDEyLjgxMywyOC41NjMsMjguNTYzQzExMy4wOTQsMTAwLjI4MSwxMDAuMjgsMTEzLjA5Myw4NC41MzEsMTEzLjA5M3oiIGZpbGw9IiNmNjg2OWUiIGRhdGEtb3JpZ2luYWw9IiMwMDAwMDAiIHN0eWxlPSIiPjwvcGF0aD4KCTxwYXRoIGQ9Ik0xMjkuOTIxLDI4LjI1MWMtMi44OSwwLTUuNzI5LDEuMTctNy43NywzLjIyYy0yLjA1MSwyLjA0LTMuMjMsNC44OC0zLjIzLDcuNzhjMCwyLjg5MSwxLjE4LDUuNzMsMy4yMyw3Ljc4ICAgYzIuMDQsMi4wNCw0Ljg4LDMuMjIsNy43NywzLjIyYzIuOSwwLDUuNzMtMS4xOCw3Ljc4LTMuMjJjMi4wNS0yLjA1LDMuMjItNC44OSwzLjIyLTcuNzhjMC0yLjktMS4xNy01Ljc0LTMuMjItNy43OCAgIEMxMzUuNjYxLDI5LjQyMSwxMzIuODIxLDI4LjI1MSwxMjkuOTIxLDI4LjI1MXoiIGZpbGw9IiNmNjg2OWUiIGRhdGEtb3JpZ2luYWw9IiMwMDAwMDAiIHN0eWxlPSIiPjwvcGF0aD4KPC9nPgo8ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgo8L2c+CjxnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjwvZz4KPGcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPC9nPgo8ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgo8L2c+CjxnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjwvZz4KPGcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPC9nPgo8ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgo8L2c+CjxnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjwvZz4KPGcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPC9nPgo8ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgo8L2c+CjxnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjwvZz4KPGcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPC9nPgo8ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgo8L2c+CjxnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjwvZz4KPGcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPC9nPgo8L2c+PC9zdmc+" class="instagram"/></a>
                    </div>
                    <div class="icon__mob">
                        <a href="https://www.tiktok.com/@ankarave?"><img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEuMSIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHhtbG5zOnN2Z2pzPSJodHRwOi8vc3ZnanMuY29tL3N2Z2pzIiB3aWR0aD0iNTEyIiBoZWlnaHQ9IjUxMiIgeD0iMCIgeT0iMCIgdmlld0JveD0iMCAwIDUxMiA1MTIiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDUxMiA1MTIiIHhtbDpzcGFjZT0icHJlc2VydmUiIGNsYXNzPSIiPjxnPjxwYXRoIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgZD0ibTQ3NS4wNzQgMGgtNDM4LjE0OGMtMjAuMzk1IDAtMzYuOTI2IDE2LjUzMS0zNi45MjYgMzYuOTI2djQzOC4xNDhjMCAyMC4zOTUgMTYuNTMxIDM2LjkyNiAzNi45MjYgMzYuOTI2aDQzOC4xNDhjMjAuMzk1IDAgMzYuOTI2LTE2LjUzMSAzNi45MjYtMzYuOTI2di00MzguMTQ4YzAtMjAuMzk1LTE2LjUzMS0zNi45MjYtMzYuOTI2LTM2LjkyNnptLTkwLjgyNyAxOTUuOTU5djM0LjYxM2MtMTYuMzIyLjAwNi0zMi4xODEtMy4xOTItNDcuMTM3LTkuNTAzLTkuNjE3LTQuMDYtMTguNTc3LTkuMjkyLTI2Ljc3Mi0xNS42MTNsLjI0NiAxMDYuNTQyYy0uMTAzIDIzLjk5MS05LjU5NCA0Ni41MzItMjYuNzcyIDYzLjUxLTEzLjk4IDEzLjgyLTMxLjY5NSAyMi42MDktNTAuODk1IDI1LjQ1My00LjUxMi42NjgtOS4xMDMgMS4wMTEtMTMuNzQ2IDEuMDExLTIwLjU1MyAwLTQwLjA2Ny02LjY1OS01Ni4wMjktMTguOTQzLTMuMDA0LTIuMzEzLTUuODc2LTQuODItOC42MTItNy41MjEtMTguNjE3LTE4LjQtMjguMjE3LTQzLjM0LTI2LjYwMS02OS41NzUgMS4yMzQtMTkuOTcxIDkuMjI5LTM5LjAxNyAyMi41NTgtNTMuOTQ1IDE3LjYzNS0xOS43NTQgNDIuMzA2LTMwLjcxOSA2OC42ODQtMzAuNzE5IDQuNjQzIDAgOS4yMzQuMzQ4IDEzLjc0NiAxLjAxN3YxMi43OTggMzUuNjAxYy00LjI3Ny0xLjQxMS04Ljg0Ni0yLjE4Ny0xMy42MDMtMi4xODctMjQuMSAwLTQzLjU5NyAxOS42NjItNDMuMjM3IDQzLjc3OS4yMjggMTUuNDMxIDguNjU4IDI4LjkyIDIxLjA5IDM2LjM1NSA1Ljg0MiAzLjQ5NSAxMi41NjQgNS42NTkgMTkuNzM3IDYuMDUzIDUuNjIuMzA4IDExLjAxNi0uNDc0IDE2LjAxMy0yLjEyNCAxNy4yMTgtNS42ODggMjkuNjM5LTIxLjg2MSAyOS42MzktNDAuOTM1bC4wNTctNzEuMzQ2di0xMzAuMjUyaDQ3LjY2OGMuMDQ2IDQuNzIzLjUyNSA5LjMzMiAxLjQxNiAxMy43OTcgMy41OTggMTguMDc1IDEzLjc4NiAzMy43NTcgMjcuOTY2IDQ0LjQ0OCAxMi4zNjQgOS4zMjYgMjcuNzYgMTQuODU0IDQ0LjQ0OCAxNC44NTQuMDExIDAgLjE0OCAwIC4xMzctLjAxMXYxMi44NDN6IiBmaWxsPSIjZjY5NjhlIiBkYXRhLW9yaWdpbmFsPSIjMDAwMDAwIiBzdHlsZT0iIiBjbGFzcz0iIj48L3BhdGg+PC9nPjwvc3ZnPg==" class="instagram"/></a>
                    </div>
            </div>
        </div>
        
        <div class="container__navigationmob">
                <div class="container__list">
                    <h2 class="contac">Navegacion</h2>
                    <nav>
                        <ul class="list">
                            <div class="about__container ad">
                                <li><Nuxt-link to="/" class="lnk">Home</Nuxt-link></li>
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
        
        <div class="copyright">
            <h1 class="copyright__text"> Copyright Ankara 2018 C.A.</h1>
        </div>
    </section>
</template>

<style>

.run{
    max-width: 100%;
    height: 100%;
    background: linear-gradient(white 60%, #facbc6);
    border-top: 1px solid #facbc6;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.container__Footermob{
    width: 90%;
    height: 3.5em;
    display: flex;
    justify-content: flex-start;
    align-items: center;
}

.Logo__Ankara{
width: 60%;
}

.subcontain__text{
    font-size: 18px;
}

.container__direction{
    width: 90%;
    height: 6.5em;
    padding-top: 0.5em;
    display: flex;
    justify-content: center;
    align-content: center;
}

.subcontainer__direction{
    height: 100%;
}

.ac{
    width: 10%;
}

.b{
    width: 90%;
}

.mapa{
    width: 2.4em;
    padding-top: 0.5em;
}

.subcontain__text{
    font-family: 'Lato', sans-serif;
    font-weight: 700;
    padding-top: 0.5em;
}

.container__contactmob{
    width: 90%;
    height: 7em;
    display: flex;
    align-items: center;
    flex-direction: column;
}


.container__iconsmob{
    width: 22%; 
    height: 4em;
    display: flex;
    justify-content: space-between;
    align-content: center;
}

.icon__mob{
    width: 2.8em;
    height: 100%;
    padding-top: 0.9em;
}

.links{
    font-family: 'Lato', sans-serif;
    font-weight: 700;
}

.container__navigationmob{
    width: 90%;
    height: 7.5em;
}

.ad{
    font-size: 18px;
}

@media (min-width: 920px) {
    .run{
        display: none;
    }
}
</style>