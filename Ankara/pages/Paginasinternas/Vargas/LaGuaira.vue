<template>
    <div>
        <header>

        <Head />

        <nav>
            <div class="logo">
            <img src="@/static/ankara_pink.svg" alt="Ankara_logo" class="logo-a">
            </div>
            <input type="checkbox" id="click">
            <label for="click" class="menu-btn">
            <i class="fas fa-bars"></i>
            </label>
            <ul>
                <li><Nuxt-link to="/">Home</Nuxt-link></li>
                <li><Nuxt-link to="/About">About</Nuxt-link></li>
                <li><Nuxt-link to="/Stores">Stores</Nuxt-link></li>
                <li><a href="#">Gallery</a></li>
                <li><a href="#">Feedback</a></li>
            </ul>
        </nav>

        </header>

        <body>
          <InternalpagesVargasLaGuaira />
        </body>

        <footer>
          
          <Footer />

          <Footermob />
          
        </footer>
    </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@1,700&family=Poppins&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,300;1,300&display=swap');
*{
  margin: 0 ;
  padding: 0 ;
  box-sizing: border-box ;
} 

nav{
  display: flex;
  height: 80px;
  width: 100%;
  background: #1b1b1b;
  align-items: center;
  justify-content: space-between;
  padding: 0 50px 0 100px;
  flex-wrap: wrap;
  font-family: 'Lato', sans-serif;
}

.logo-a{
  width: 4em;
}

nav .logo{
  color: #fff;
  font-size: 35px;
  font-weight: 600;
}
nav ul{
  display: flex;
  flex-wrap: wrap;
  list-style: none;
}
nav ul li{
  margin: 0 5px;
}
nav ul li a{
  color: #f2f2f2;
  text-decoration: none;
  font-size: 18px;
  font-weight: 500;
  padding: 8px 15px;
  border-radius: 5px;
  letter-spacing: 1px;
  transition: all 0.3s ease;
  font-weight: bold;
}
nav ul li a.active,
nav ul li a:hover{
  color: #111;
  background: #fff;
}
nav .menu-btn i{
  color: #fff;
  font-size: 22px;
  cursor: pointer;
  display: none;
}
input[type="checkbox"]{
  display: none;
}
@media (max-width: 1000px){
  nav{
    padding: 0 40px 0 50px;
  }
}
@media (max-width: 920px) {
  nav .menu-btn i{
    display: block;
  }
  #click:checked ~ .menu-btn i:before{
    content: "\f00d";
  }
  nav ul{
    position: fixed ;
    top: 80px ;
    left: -100% ;
    background: #111 ;
    height: 100vh ;
    width: 100% ;
    text-align: center ;
    display: block ;
    transition: all 0.3s ease ;
  }
  #click:checked ~ ul{
    left: 0;
  }
  nav ul li{
    width: 100%;
    margin: 40px 0;
  }
  nav ul li a{
    width: 100% ;
    margin-left: -100% ;
    display: block ;
    font-size: 20px ;
    transition: 0.6s cubic-bezier(0.68, -0.55, 0.265, 1.55) ;
  }
  #click:checked ~ ul li a{
    margin-left: 0px;
  }
  nav ul li a.active,
  nav ul li a:hover{
    background: none;
    color: cyan;
  }
}
.content{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  z-index: -1;
  width: 100%;
  padding: 0 30px;
  color: #1b1b1b;
}
.content div{
  font-size: 40px;
  font-weight: 700;
}
</style>