<template>
    <div class="body__container">
        <div class="container__card">
            <div class="card__contain">
                <div class="contain__photo">
                    <img src="@/static/ANKARA.svg" alt="logo ankara">   
                </div>
                <div class="contain__txt">
                    <h1 class="txt__title">Casco Central</h1>

                    <h2 class="txt__subtitle">Anzoategui</h2>

                    <p>Av. Boulevard 5 de Julio. Local N°1. Zona Casco Central.</p>

                    <Nuxt-link to="/Paginasinternas/Anzoategui/Cascocentral"><button class="button__card">Visitar Tienda</button></Nuxt-link>
                </div>
            </div>

            <div class="card__contain">
                <div class="contain__photo">
                    <img src="@/static/ANKARA.svg" alt="logo ankara">
                </div>
                <div class="contain__txt">
                    <h1 class="txt__title">Sector Centro</h1>

                    <h2 class="txt__subtitle">Anzoategui</h2>

                    <p>Calle Buenos Aires con calle Libertad. Local 48. Sector Centro. Frente a la tienda Wrangler.  </p>

                    <Nuxt-link to="/Paginasinternas/Anzoategui/Sectorcentro"><button class="button__card">Visitar Tienda</button></Nuxt-link>
                </div>
            </div>
        </div>
    </div>
</template>

