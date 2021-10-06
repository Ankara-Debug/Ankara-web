<template>
    <div class="container__team">
        <div class="container__items">
            <div class="subcontainer__team">

            </div>
            <div class="subcontainer__subimg">
                <div class="subcontainer__text">
                    <div class="subcontain">
                            <p >Deseas <span class="span"> formar parte </span></p>
                    </div>
                    <div class="subcontain__subtext">
                        <p >de nuestro equipo?</p>
                    </div>
                    <div class="send">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style>

@font-face {
    font-family: photo;
    src: url(@/static/Photoshoot.ttf);
}

.container__team{
    width: 100%;
    height: 43em;
    display: flex;
    justify-content: center;
    align-items: center;    
}

.subcontainer__team{
    width: 95%;
    height: 80%;
    background-color: #f6968e;
    border-top-right-radius: 120px;
    border-bottom-left-radius: 120px;
}

.container__items{
    width: 80%;
    height: 60%;
}

.subcontainer__subimg{
    width: 95%;
    height: 85%;
    background-color: #facbc6;
    border-top-right-radius: 120px;
    border-bottom-left-radius: 120px;
    position: relative;
    top: -280px;
    right: -50px;
    display: flex;
    align-content: flex-end;
    justify-content: flex-end;
}

.subcontainer__text{
    width: 65%;
    height: 100%;
}

.team__text{
    color: black;
    font-family: 'Lato', sans-serif;
    font-size: 45px;
    font-weight: bold;    
}

.subcontain__subtext{
    width: 100%;
    padding-left: 3.5em;
    color: black;
    font-family: 'Lato', sans-serif;
    font-size: 45px;
    display: flex;
    font-weight: bold;
}

.subcontain{
    width: 100%;
    padding-top: 0.5em;
    color: black;
    font-family: 'Lato', sans-serif;
    font-size: 45px;
    height: 1.6em;
    font-weight: bold;
}

.span{
    font-family: 'Lato', sans-serif;
    color: #f5867d;
    font-weight: bold;
}

.send{
    width: 100%;
    height: 2em;
}

@media (max-width: 920px) {

    .container__team{
        max-width: 100%;
    }

    .container__items{
        width: 90%;
    }

    .subcontainer__subimg{
        right: -25px;
    }

    .subcontain__subtext{
        font-size: 30px;
        padding-left: 2em;

    }

    .subcontain{
        font-size: 30px;
        padding-left: 0.5em;
    }

    .subcontainer__subimg{
        display: flex;
        justify-content: flex-start;
    }

    .subcontainer__text{
        width: 100%;
    }
}
</style>