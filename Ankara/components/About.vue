<template>
    <div>
        <section class="about">
            <div class="container__1">
                <p class="text__title">Tu belleza nos 
                    inspira
                </p>
            </div>
            <div class="container__2">
                <div class="subcontainer__1">
                    <div class="container__icon">
                        <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEuMSIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHhtbG5zOnN2Z2pzPSJodHRwOi8vc3ZnanMuY29tL3N2Z2pzIiB3aWR0aD0iNTEyIiBoZWlnaHQ9IjUxMiIgeD0iMCIgeT0iMCIgdmlld0JveD0iMCAwIDUxMiA1MTIiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDUxMiA1MTIiIHhtbDpzcGFjZT0icHJlc2VydmUiPjxnPjxnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHBhdGggZD0ibTUwMS42ODggMjMzLjQ3M2MtMjAuMjQ2LTE4LjI2MS01My4xMzUtNDQuNzM3LTk0LjgzOS02Ny4xNjctNTEuMzIzLTI3LjYwMS0xMDIuMDc2LTQxLjU5Ny0xNTAuODQ5LTQxLjU5Ny01OS4yNjEgMC0xMjAuNzEyIDIwLjMzMy0xODIuNjQ2IDYwLjQzMy0zLjQ3NyAyLjI1Mi00LjQ3MSA2Ljg5Ni0yLjIyIDEwLjM3MiAyLjI1MSAzLjQ3OCA2Ljg5NSA0LjQ2OSAxMC4zNzIgMi4yMiAzMS41NTUtMjAuNDMxIDYyLjg5Ny0zNS41MTcgOTMuNzgxLTQ1LjE3Ny0zMC43NTYgMjQuMDQ3LTUwLjU3NyA2MS40NjUtNTAuNTc3IDEwMy40NDMgMCA0MS44MjcgMTkuNjc3IDc5LjEyOCA1MC4yNDQgMTAzLjE4NS03MS41LTIyLjU1OC0xMjguODExLTY4LjU0Mi0xNTQuNTkzLTkxLjc5Ny0zLjQ1Ny0zLjExNy01LjM2LTcuMTYyLTUuMzYtMTEuMzg5IDAtNC4yMjUgMS45MDMtOC4yNzEgNS4zNi0xMS4zODggMTEuMzU0LTEwLjI0IDIzLjUzNi0yMC4xOTIgMzYuMjA4LTI5LjU4MSAzLjMyOC0yLjQ2NiA0LjAyNy03LjE2MyAxLjU2Mi0xMC40OTEtMi40NjYtMy4zMjctNy4xNjItNC4wMjQtMTAuNDkxLTEuNTYyLTEzLjA1NyA5LjY3NC0yNS42MTUgMTkuOTM0LTM3LjMyNSAzMC40OTUtNi42NTIgNi0xMC4zMTUgMTQtMTAuMzE1IDIyLjUyNyAwIDguNTI4IDMuNjYzIDE2LjUyOCAxMC4zMTQgMjIuNTI3IDIwLjI0NiAxOC4yNjEgNTMuMTM0IDQ0LjczNyA5NC44MzkgNjcuMTY3IDUxLjMyMiAyNy42MDIgMTAyLjA3NCA0MS41OTcgMTUwLjg0OCA0MS41OTcgNTMuMDA5IDAgMTA4LjEyNS0xNi40MzkgMTYzLjgxNy00OC44NTkgMy41NzktMi4wODQgNC43OTItNi42NzUgMi43MDgtMTAuMjU1LTIuMDg1LTMuNTgtNi42NzYtNC43OTQtMTAuMjU1LTIuNzA4LTI1LjM3MyAxNC43Ny01MC41NjUgMjYuMDcxLTc1LjQyMyAzMy44NzIgMzAuNjgtMjQuMDUyIDUwLjQ0My02MS40MjIgNTAuNDQzLTEwMy4zNCAwLTQxLjgyOS0xOS42NzktNzkuMTMtNTAuMjQ4LTEwMy4xODcgNzEuNTAxIDIyLjU1OCAxMjguODE0IDY4LjU0MiAxNTQuNTk4IDkxLjc5OCAzLjQ1NiAzLjExOCA1LjM1OSA3LjE2MyA1LjM1OSAxMS4zODlzLTEuOTAzIDguMjctNS4zNTkgMTEuMzg4Yy0xMS40NjggMTAuMzQzLTMwLjA3MyAyNi4wMDUtNTMuNTkgNDEuODgyLTMuNDM0IDIuMzE3LTQuMzM4IDYuOTc5LTIuMDIgMTAuNDEyIDEuNDQ5IDIuMTQ2IDMuODE0IDMuMzA1IDYuMjIzIDMuMzA1IDEuNDQzIDAgMi45MDMtLjQxNiA0LjE4OS0xLjI4NSAyNC4yMzctMTYuMzYzIDQzLjQyLTMyLjUxIDU1LjI0NC00My4xNzUgNi42NTEtNS45OTkgMTAuMzEzLTEzLjk5OSAxMC4zMTMtMjIuNTI3cy0zLjY2Mi0xNi41MjgtMTAuMzEyLTIyLjUyN3ptLTEyOS4zOTcgMjIuNTI3YzAgNjQuMTIyLTUyLjE2OCAxMTYuMjktMTE2LjI5MSAxMTYuMjktNjQuMTIyIDAtMTE2LjI5LTUyLjE2OC0xMTYuMjktMTE2LjI5IDAtNjQuMTIzIDUyLjE2OC0xMTYuMjkxIDExNi4yOS0xMTYuMjkxIDY0LjEyMyAwIDExNi4yOTEgNTIuMTY4IDExNi4yOTEgMTE2LjI5MXoiIGZpbGw9IiNmZmZmZmYiIGRhdGEtb3JpZ2luYWw9IiMwMDAwMDAiIHN0eWxlPSIiPjwvcGF0aD48cGF0aCBkPSJtMjU2IDMyMy4wMmMzNi45NTUgMCA2Ny4wMjEtMzAuMDY1IDY3LjAyMS02Ny4wMiAwLTE2LjYxNS02LjAxNC0zMi4zMDEtMTYuOTk3LTQ0LjU5MiAxLjMxOS0zLjQzMSAyLjA0OS03LjE1MSAyLjA0OS0xMS4wNDEgMC0xNy4wMjctMTMuODUzLTMwLjg4MS0zMC44ODEtMzAuODgxLTEzLjE3NCAwLTI0LjQ0MiA4LjI5Ni0yOC44NyAxOS45MzYtMzMuNTEyIDMuODM2LTU5LjM0MiAzMi41MTItNTkuMzQyIDY2LjU3OCAwIDM2Ljk1NiAzMC4wNjUgNjcuMDIgNjcuMDIgNjcuMDJ6bTIxLjE5MS0xMzguNTMzYzguNzU3IDAgMTUuODgxIDcuMTI0IDE1Ljg4MSAxNS44ODFzLTcuMTI0IDE1Ljg4MS0xNS44ODEgMTUuODgxLTE1Ljg4MS03LjEyNC0xNS44ODEtMTUuODgxYy4wMDEtOC43NTcgNy4xMjUtMTUuODgxIDE1Ljg4MS0xNS44ODF6bS0zMC41NTMgMjAuMzQ3YzIuMTcxIDE0LjkxOCAxNS4wNDQgMjYuNDE0IDMwLjU1NCAyNi40MTQgNy41NDIgMCAxNC40NTgtMi43MjIgMTkuODI3LTcuMjMgNy4xMjYgOS4xMDIgMTEuMDAyIDIwLjI0IDExLjAwMiAzMS45ODEgMCAyOC42ODQtMjMuMzM2IDUyLjAyLTUyLjAyMSA1Mi4wMi0yOC42ODQgMC01Mi4wMi0yMy4zMzYtNTIuMDItNTIuMDIgMC0yNS4yNzkgMTguMzI0LTQ2LjcyNiA0Mi42NTgtNTEuMTY1eiIgZmlsbD0iI2ZmZmZmZiIgZGF0YS1vcmlnaW5hbD0iIzAwMDAwMCIgc3R5bGU9IiI+PC9wYXRoPjwvZz48L2c+PC9zdmc+" class="img"/>
                    </div>
                    <h2 class="subtitle">Vision</h2>
                    <div class="container__text">
                        <p>
                            "Ofrecer la mejor experiencia de belleza y bienestar, brindando una amplia variedad 
                            de marcas a nuestros clientes con el objetivo de satisfacer sus necesidades y superar 
                            sus expectativas con productos de excelente calidad".
                        </p>
                    </div>
                </div>
                <div class="subcontainer__1">
                    <div class="container__icon">
                        <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEuMSIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHhtbG5zOnN2Z2pzPSJodHRwOi8vc3ZnanMuY29tL3N2Z2pzIiB3aWR0aD0iNTEyIiBoZWlnaHQ9IjUxMiIgeD0iMCIgeT0iMCIgdmlld0JveD0iMCAwIDUxMi4wMDAyNSA1MTIiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDUxMiA1MTIiIHhtbDpzcGFjZT0icHJlc2VydmUiIGNsYXNzPSIiPjxnPjxwYXRoIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgZD0ibTQ2MC44MDA3ODEgMjQ2Ljg3ODkwNiA1MC4wNzgxMjUtODEuMjg1MTU2YzMuMDcwMzEzLTQuOTg0Mzc1LS41MjM0MzctMTEuNDMzNTk0LTYuMzg2NzE4LTExLjQzMzU5NGgtMTUxLjQxNzk2OXYtMTcuNjc5Njg3YzAtMTYuNTcwMzEzLTEzLjQ3NjU2My0zMC4wNTA3ODEtMzAuMDUwNzgxLTMwLjA1MDc4MWgtMTk5LjAyNzM0NHYtMjIuNzMwNDY5aDIuNjUyMzQ0YzEyLjMyNDIxOCAwIDIyLjM0NzY1Ni0xMC4wMjczNDQgMjIuMzQ3NjU2LTIyLjM1MTU2M3YtMTEuNTk3NjU2YzAtMjcuNDMzNTk0LTIyLjMxNjQwNi00OS43NS00OS43NDYwOTQtNDkuNzVoLTE4LjVjLTI3LjQzMzU5NCAwLTQ5Ljc1IDIyLjMxNjQwNi00OS43NSA0OS43NXYxMS42MDE1NjJjMCAxMi4zMjAzMTMgMTAuMDIzNDM4IDIyLjM0NzY1NyAyMi4zNDc2NTYgMjIuMzQ3NjU3aDIuNjUyMzQ0djgwLjU5NzY1NmMwIDQuMTQ0NTMxIDMuMzU1NDY5IDcuNSA3LjUgNy41IDQuMTQwNjI1IDAgNy41LTMuMzU1NDY5IDcuNS03LjV2LTgwLjU5NzY1NmgzOHYzNjIuNzkyOTY5aC0zOHYtMjU0LjE5OTIxOWMwLTQuMTQwNjI1LTMuMzU5Mzc1LTcuNS03LjUtNy41LTQuMTQ0NTMxIDAtNy41IDMuMzU5Mzc1LTcuNSA3LjV2MjU0LjE5OTIxOWgtMzQuNWMtMTEuODU1NDY5IDAtMjEuNSA5LjY0NDUzMS0yMS41IDIxLjV2MjIuNWMwIDExLjg1NTQ2OCA5LjY0NDUzMSAyMS41IDIxLjUgMjEuNWgxMzYuOTk2MDk0YzExLjg1NTQ2OCAwIDIxLjUtOS42NDQ1MzIgMjEuNS0yMS41di0yMi41YzAtMTEuODU1NDY5LTkuNjQ0NTMyLTIxLjUtMjEuNS0yMS41aC0zNC41di0xNTQuNjI4OTA3aDE0Mi41djE3LjY4MzU5NGMwIDE2LjU3MDMxMyAxMy40ODA0NjggMzAuMDUwNzgxIDMwLjA1MDc4MSAzMC4wNTA3ODFoMTAyLjYxNzE4N2M0LjE0NDUzMiAwIDcuNS0zLjM1OTM3NSA3LjUtNy41IDAtNC4xNDQ1MzEtMy4zNTU0NjgtNy41LTcuNS03LjVoLTEwMi42MTcxODdjLTguMzAwNzgxIDAtMTUuMDUwNzgxLTYuNzUzOTA2LTE1LjA1MDc4MS0xNS4wNTA3ODF2LTE3LjY4MzU5NGg0MS41MjczNDRjMTYuNTcwMzEyIDAgMzAuMDUwNzgxLTEzLjQ3NjU2MiAzMC4wNTA3ODEtMzAuMDQ2ODc1di05Mi42NTIzNDRoMTM3Ljk4ODI4MWwtNDUuNDU3MDMxIDczLjc4MTI1Yy0xLjQ4NDM3NSAyLjQxNDA2My0xLjQ4NDM3NSA1LjQ1NzAzMiAwIDcuODY3MTg4bDQ1LjQ1NzAzMSA3My43ODUxNTZoLTYzLjg5ODQzOGMtNC4xNDA2MjQgMC03LjUgMy4zNTU0NjktNy41IDcuNSAwIDQuMTQwNjI1IDMuMzU5Mzc2IDcuNSA3LjUgNy41aDc3LjMyODEyNmM1Ljg1NTQ2OCAwIDkuNDYwOTM3LTYuNDM3NSA2LjM4NjcxOC0xMS40MzM1OTR6bS00MDcuNDUzMTI1LTE3OC4xNzk2ODdjLTQuMDUwNzgxIDAtNy4zNDc2NTYtMy4yOTY4NzUtNy4zNDc2NTYtNy4zNTE1NjN2LTExLjU5NzY1NmMwLTE5LjE2MDE1NiAxNS41ODk4NDQtMzQuNzUgMzQuNzUtMzQuNzVoMTguNWMxOS4xNjAxNTYgMCAzNC43NDYwOTQgMTUuNTg5ODQ0IDM0Ljc0NjA5NCAzNC43NXYxMS41OTc2NTZjMCA0LjA1NDY4OC0zLjI5Njg3NSA3LjM1MTU2My03LjM0NzY1NiA3LjM1MTU2M3ptMTExLjY0ODQzOCAzOTkuMjkyOTY5djIyLjVjMCAzLjU4NTkzNy0yLjkxNDA2MyA2LjUtNi41IDYuNWgtMTM2Ljk5NjA5NGMtMy41ODU5MzggMC02LjUtMi45MTQwNjMtNi41LTYuNXYtMjIuNWMwLTMuNTgyMDMyIDIuOTE0MDYyLTYuNSA2LjUtNi41aDEzNi45OTYwOTRjMy41ODU5MzcgMCA2LjUgMi45MTc5NjggNi41IDYuNXptMTczLjA3ODEyNS0yMDYuMTc1NzgyYzAgOC4yOTY4NzUtNi43NSAxNS4wNTA3ODItMTUuMDUwNzgxIDE1LjA1MDc4MmgtMTk5LjAyNzM0NHYtMTU1LjQzNzVoMTk5LjAyNzM0NGM4LjMwMDc4MSAwIDE1LjA1MDc4MSA2Ljc1MzkwNiAxNS4wNTA3ODEgMTUuMDUwNzgxem0wIDAiIGZpbGw9IiNmZmZmZmYiIGRhdGEtb3JpZ2luYWw9IiMwMDAwMDAiIHN0eWxlPSIiIGNsYXNzPSIiPjwvcGF0aD48L2c+PC9zdmc+" class="img"/>
                    </div>
                    <h2 class="subtitle">Mision</h2>
                    <div class="container__text">
                        <p>
                            "Ser la empresa líder de belleza en el mercado venezolano, convirtiéndonos en la 
                            mejor opción de los clientes con productos de calidad, e identificarnos por nuestro
                            profesionalismo y excelente servicio".
                        </p>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<style>
    @font-face {
        font-family: Photo;
        src: url(@/static/Photoshoot.ttf);
    }
    .about{
        width: 100%;
        height: 80vh;
        background-color: #facbc6;
        display: flex;
    }

    .container__1{
        width: 50%;
        height: 30%;
    }

    .container__2{
        width: 50%;
        height: 100%;
    }

    .subcontainer__1 {
        width: 100%;
        height: 50%;
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .text__title{
        font-family: Photo;
        font-size: 40px;
        text-align: center;
        padding-top: 1em;
        width: 100%;
        height: 100%;
    }

    .container__icon{
        width: 4em;
        height: 4em;
        margin-top: 1em;
        border-radius: 60%;
        background-color: #f36c63;
        display: flex;
        justify-content: center;
        align-content: center;
    }

    .img{
        width: 70%;
    }

    .container__text{
        width: 83%;
        height: 60%;
        font-size: 20px;
        text-align: center;
        font-family: 'Lato', sans-serif;
        font-weight: 700;
    }

    .subtitle{
       font-family: 'Lato', sans-serif; 
       font-weight: bold;
    }

@media  screen and (max-width: 920px){

    .about{
        width: 100%;
        height: 120vh;
        background-color: #facbc6;
        display: flex;
        flex-direction: column;
    }

    .container__1{
        width: 100%;
        height: 20%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .container__2{
        width: 100%;
        height: 80%;
    }

    .container__icon{
        width: 4em;
        height: 4em;
    }

    .text__title{
        font-size: 35px;
        height: 50%;
    }
}
</style>