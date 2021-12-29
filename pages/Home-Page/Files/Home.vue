<template>
  <b-container-fluid>
    <b-row>
      <b-col>
        <b-navbar class="navbar" toggleable="lg" type="light" variant="light">
          <b-navbar-brand class="mainlogo" href="#"
            ><img src="@/pages/Home-Page/Images/MainLogo.svg"
          /></b-navbar-brand>

          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
          <b-collapse id="nav-collapse" is-nav>
            <!-- <b-navbar-nav>
              <b-nav-item href="#">Link</b-nav-item>
              <b-nav-item href="#" disabled>Disabled</b-nav-item>
            </b-navbar-nav> -->

            <!-- Right aligned nav items -->
            <b-navbar-nav class="ml-auto">
              <b-nav-item class="n-items"
                ><a href="#" class="active"> Home </a></b-nav-item
              >
              <b-nav-item class="n-items"
                ><a href="#"> Dra. Marcela Vejarano </a></b-nav-item
              >
              <b-nav-item class="n-items"
                ><a href="#"> Tratamientos </a></b-nav-item
              >
              <b-nav-item class="n-items"
                ><a href="#"> Testimonios </a></b-nav-item
              >
              <b-nav-item class="n-items"
                ><a href="#"> Antes y Después </a></b-nav-item
              >
              <b-nav-item class="n-items headphone"
                ><a href="#">
                  <img
                    src="@/pages/Home-Page/Images/headphonelogo.svg"
                    alt="headphonelogo"
                  /><span>Contacto</span></a
                >
              </b-nav-item>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar></b-col
      >
    </b-row>
    <b-row>
      <b-col col sm="6" lg="6" md="6" xl="6" class="body-image-1">
        <img src="@/pages/Home-Page/Images/sonrisa.jpg" alt="body-image" />
      </b-col>
      <b-col col sm="6" lg="6" md="6" xl="6" class="body-image-col-6">
        <h1 class="text-center">Lentes Cerámicos</h1>
        <div class="line"></div>
        <img src="@/pages/Home-Page/Images/Group.svg" alt="svg" />
      </b-col>
    </b-row>
    <b-row>
      <b-col cols="6" class="body-image-2">
        <img
          src="@/pages/Home-Page/Images/body-image-2.png"
          alt="body-image-2"
        />
      </b-col>
      <b-col cols="6" class="col-div-form">
        <div class="div-form">
          <form action="">
            <label><span>Asesoría Personalizada </span> #SonrisaVejarano</label>
            <input type="text" placeholder="*Nombre" />
            <input type="text" placeholder="*Correo electrónico" />
            <input type="text" placeholder="*Apellido" />
            <input type="text" placeholder="*País" />
            <input type="text" placeholder="*Teléfono " />
            <input type="text" class="color-input" placeholder="Enviar" />
          </form>
        </div>
      </b-col>
    </b-row>
    <b-row>
      <b-col>
        <h1 class="text-center h1-text">Casos de éxito</h1>
      </b-col>
    </b-row>
    <b-row class="b-row-2">
      <b-col cols="8" class="b-col-2">
        <div class="div-1">
          <div class="div-2">
            <img src="@/pages/Home-Page/Images/Image-4.jpg" />
          </div>
          <div class="div-3">
            <p>Lorem ipsum</p>
            <button>Ver</button>
          </div>
        </div>
        <div class="div-1">
          <div class="div-2">
            <img src="@/pages/Home-Page/Images/Image-4.jpg" />
          </div>
          <div class="div-3">
            <p>Lorem ipsum</p>
            <button right>Ver</button>
          </div>
        </div>
        <div class="div-1">
          <div class="div-2">
            <img src="@/pages/Home-Page/Images/Image-4.jpg" />
          </div>
          <div class="div-3">
            <p>Lorem ipsum</p>
            <button>Ver</button>
          </div>
        </div>
        <div class="div-1">
          <div class="div-2">
            <img src="@/pages/Home-Page/Images/Image-4.jpg" />
          </div>
          <div class="div-3">
            <p>Lorem ipsum</p>
            <button>Ver</button>
          </div>
        </div>
      </b-col>
    </b-row>
    <b-row>
      <b-col>
        <div class="text-center h1-second-div">
          <h1 class="h1-second">Cambios Fabulosos</h1>
        </div>
      </b-col>
    </b-row>
    <b-row class="b-row-3">
      <b-col class="b-col-3" cols="8">
        <div class="a1">
          <div>
            <img
              src="@/pages/Home-Page/Images/Teeth/1.svg"
              alt="Diseño de
Sonrísa"
            />
            <p>Diseño de Sonrísa</p>
          </div>
        </div>
        <div class="a1">
          <div>
            <img
              src="@/pages/Home-Page/Images/Teeth/2.svg"
              alt="Estética
Dental"
            />
            <p>Estética Dental</p>
          </div>
        </div>
        <div class="a1">
          <div>
            <img
              src="@/pages/Home-Page/Images/Teeth/3.svg"
              alt="Rehabilitación
Oral"
            />
            <p>Rehabilitación Oral</p>
          </div>
        </div>
        <div class="a1">
          <div>
            <img
              src="@/pages/Home-Page/Images/Teeth/4.svg"
              alt="Implantología
Dental"
            />
            <p>Implantología Dental</p>
          </div>
        </div>
        <div class="a1">
          <div>
            <img src="@/pages/Home-Page/Images/Teeth/5.svg" alt="Ortodoncia" />
            <p>Ortodoncia</p>
          </div>
        </div>
        <div class="a1">
          <div>
            <img
              src="@/pages/Home-Page/Images/Teeth/6.svg"
              alt="Blanqueamiento
Dental"
            />
            <p>Blanqueamiento Dental</p>
          </div>
        </div>
        <div class="a1">
          <div>
            <img
              src="@/pages/Home-Page/Images/Teeth/7.svg"
              alt="Cirugía
Maxilofacial"
            />
            <p>Cirugía Maxilofacial</p>
          </div>
        </div>
        <div class="a1">
          <div>
            <img src="@/pages/Home-Page/Images/Teeth/8.svg" alt="Endodoncia" />
            <p>Endodoncia</p>
          </div>
        </div>
        <div class="a1">
          <div>
            <img src="@/pages/Home-Page/Images/Teeth/9.svg" alt="Periodoncia" />
            <p>Periodoncia</p>
          </div>
        </div>
        <div class="a1-change">
          <div>
            <img
              src="@/pages/Home-Page/Images/Teeth/10.svg"
              alt="Asesoría
Personalizada"
            />
            <p>Asesoría Personalizada</p>
          </div>
        </div>
      </b-col>
    </b-row>
    <b-row>
      <b-col class="text-center h1-second">
        <p>#SonrisaVejarano</p>
      </b-col>
    </b-row>
    <b-row class="b-row-4">
      <b-col cols="8" class="col-4-div">
        <div class="a2">
          <img src="@/pages/Home-Page/Images/slider.jpg" alt="" />
        </div>
        <div class="a2">
          <img src="@/pages/Home-Page/Images/slider.jpg" alt="" />
        </div>
        <div class="a2">
          <img src="@/pages/Home-Page/Images/slider.jpg" alt="" />
        </div>
      </b-col>
    </b-row>
    <b-row class="text-center b-row-5">
      <b-col class="b-col-5">
        <img src="@/pages/Home-Page/Images/10.svg" alt="" />
      </b-col>
    </b-row>
    <b-row>
      <b-col>
        <h1 class="text-center h1-text">Asesoría Online</h1>
      </b-col>
    </b-row>
    <b-row class="b-row-6">
      <b-col cols="3">
        <h1 class="h2-text">+57 320 8037031</h1>
      </b-col>
    </b-row>
    <b-row class="b-row-7">
      <b-col class="b-col-7" cols="3">
        <div>
          <a href="#" target="blank"
            ><img
              src="@/pages/Home-Page/Images/Social/telegram.png"
              alt="telegram"
          /></a>
          </div>
          <div>
          <a href="#" target="blank"
            ><img
              src="@/pages/Home-Page/Images/Social/messenger.png"
              alt="messenger"
          /></a>
          </div>
          <div>
          <a href="#" target="blank"
            ><img
              src="@/pages/Home-Page/Images/Social/instagram.png"
              alt="instagram"
          /></a>
          </div>
          <div>
          <a href="#" target="blank"
            ><img
              src="@/pages/Home-Page/Images/Social/whatsapp.png"
              alt="whatsapp"
          /></a>
          </div>
        </b-col>
      </b-col>
    </b-row>
  </b-container-fluid>
</template>
<script setup lang="js">
import mainlogo from '@/pages/Home-Page/Images/sonrisa.jpg';
export default {
  components:
  {
    mainlogo
  },
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap');

* {
  color: none;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.mainlogo img {
  margin-left: 100px;
  height: 90%;
  width: 70%;
}
.navbar {
  position: fixed;
  height: 18vh;
  width: 100vw;
  z-index: 1;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}
.navbar .ml-auto {
  margin-right: 100px;
}
.n-items a {
  font-size: 17px;
  font-weight: 400;
  text-decoration: none;
  text-transform: capitalize;
  margin-right: 15px;
  font-weight: 500;
  color: black;
}
/* .n-items a:hover,
a.active {
  color: #ffbe34;
  font-weight: 800;
} */
.headphone img {
  height: 15%;
  width: 15%;
  margin-right: 3px;
}
.headphone span {
  color: white;
  font-weight: 900;
}
.headphone {
  border-radius: 5px;
  background-color: black;
  height: 34px;
  width: 150px;
}
.body-image-1 img {
  margin-top: 110px;
  width: 180%;
  height: auto;
}
.body-image-col-6 {
  display: grid;
  margin-top: 140px;
  justify-content: center;
  justify-items: center;
}
.body-image-col-6 h1 {
  font-size: 8em;
  font-weight: bold;
  color: var(--unnamed-color-000000);
  text-align: center;
  font-family: 'Playfair Display', serif;
  letter-spacing: 0px;
  color: #000000;
  text-shadow: 0px -3px 6px #0000002e;
  opacity: 1;
}
.line {
  position: relative;
  top: -40px;
  width: 36em;
  height: 3px;
  background: #ffbe34;
  border: 1px solid var(--unnamed-color-ffbe34);
  border: 1px solid #ffbe34;
  opacity: 1;
}
.body-image-col-6 img {
  position: relative;
  top: -80px;
  text-align: center;
  font-size: 2.75rem;
  opacity: 1;
  font-family: 'Playfair Display', serif;
}
.body-image-2 img {
  height: auto;
  width: 99vw;
  margin-top: -52px;
  margin-left: -4px;
}
.div-form {
  position: relative;
  text-align: center;
  border-radius: 5px;
  top: 70px;
  left: -25em;
  width: -30em;
  height: 50vh;
}
.div-form label {
  display: flex;
  font-size: 2em;
  height: 100px;
  align-content: center;
  align-items: center;
  background: white;
  color: black;
}
.div-form label span {
  text-align: center;
  margin-left: 40px;
  margin-right: 20px;
  font-weight: 600;
}
form input {
  text-align: center;
  font-size: 20px;
  height: 65px;
  width: 370px;
  margin: 3px;
  border-radius: 5px;
}
form input.color-input {
  background: #ffbe34;
  font-weight: 600;
}
form {
  margin-top: 20px;
  border-radius: 5px;
  border: 2px solid #fff;
}
.h1-text {
  height: 200px;
  color: var(--unnamed-color-000000);
  text-align: center;
  font: normal normal bold 100px/129px Playfair Display;
  letter-spacing: 0px;
  color: #000000;
  opacity: 1;
}
.b-row-2 {
  /* display: flex; */
  /* border: 1px solid red; */
  justify-content: center;
}
.b-col-2 {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  height: 350px;
  width: 50em;
}

.b-col-2 .div-1 {
  display: flex;
  height: 10em;
  width: 30em;
  background: #efefef;
  border-radius: 10px;
  padding: 7px;
  margin: 5px;
}
.b-col-2 .div-3 {
  width: 15em;
  height: 12em;
}
.b-col-2 .div-3 button {
  margin-top: 20px;
  margin-left: 10px;
  width: 200px;
  height: 50px;
  /* background: var(--unnamed-color-ffffff) 0% 0% no-repeat padding-box; */
  background: #ffffff 0% 0% no-repeat padding-box;
  box-shadow: 0px 2px 2px #0000000f;
  border-radius: 5px;
  opacity: 1;
}
.b-col-2 .div-3 p {
  width: 208px;
  height: 46px;
  font: normal normal bold 34px/74px Outfit;
  text-align: center;
  letter-spacing: 0px;
  color: #000000;
  opacity: 1;
}
.h1-second-div {
  height: 200px;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.h1-second {
  color: var(--unnamed-color-000000);
  text-align: center;
  font: normal normal bold 100px/119px Playfair Display;
  letter-spacing: 0px;
  color: #000000;
  opacity: 1;
}
.b-col-3 {
  height: 70vh;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
}
.b-row-3 {
  height: 70vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
.b-col-3 .a1 {
  background: #efefef 0% 0% no-repeat padding-box;
  border-radius: 10px;
  opacity: 1;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 240px;
  width: 185px;
}
.b-col-3 .a1 div img {
  margin-left: 20px;
  margin-bottom: 20px;
  width: 100px;
  height: 99px;
  opacity: 1;
}
.b-col-3 .a1 div p {
  width: 120px;
  color: var(--unnamed-color-000000);
  text-align: center;
  font: normal normal bolder 19px/25px Outfit;
  letter-spacing: 0px;
  color: #000000;
  font: bolder;
  opacity: 1;
}
.a1-change {
  background: #000000;
  color: white;
  border-radius: 10px;
  opacity: 1;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 240px;
  width: 185px;
}
.h1-third h1 {
  color: var(--unnamed-color-000000);
  text-align: center;
  font: normal normal bold 100px/119px Playfair Display;
  letter-spacing: 0px;
  color: #000000;
  opacity: 1;
}
.b-row-4 {
  display: flex;
  justify-content: center;
}
.col-4-div {
  height: 40vh;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  justify-content: space-evenly;
}
.col-4-div .a2 {
  display: flex;
  justify-content: space-evenly;
}
.col-4-div .a2 img {
  width: 330px;
  height: 200px;
  opacity: 1;
}
.b-row-6 {
  display: flex;
  justify-content: center;
}
.h2-text {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 430px;
  height: 87px;
  font-weight: bolder;
  background: var(--unnamed-color-ffbe34) 0% 0% no-repeat padding-box;
  background: #ffbe34 0% 0% no-repeat padding-box;
  border-radius: 5px;
  opacity: 1;
}
.b-row-7 {
  border: 1px solid red;
  display: flex;
  justify-content: center;
  align-items: center;
}
.b-col-7 {
  display: flex;
  height: 20vh;
  border: 1px solid red;
  justify-content: center;
  align-items: center;
}
.b-col-7 div {
  border: 1px solid red;
  display: flex;
  justify-content: space-evenly;
}
.b-col-7 a img {
  display: flex;
  justify-content: space-between;
  /* border: 1px solid red; */
  height: 50px;
  width: 50px;
}

/******************************************************* MEDIA QUEARY ******************************************************** */
@media (max-width: 1024px) {
  .body-image-col-6 h1 {
    font-size: 6em;
  }
  .body-image-col-6 .line {
    width: 28em;
  }
  .body-image-2 img {
    margin-top: -31px;
  }
}
@media (max-width: 1440px) {
  .body-image-col-6 .line {
    top: 0px;
  }
  .body-image-col-6 img {
    top: 0px;
    width: 10em;
  }
  .line {
    width: 32em;
  }
  .n-items a {
    font-size: 1em;
    margin-right: 5px;
  }
  form input {
    height: 50px;
    width: 340px;
  }
  .div-form {
    top: 35px;
    left: -18em;
  }
}

@media (max-width: 1199px) {
  .body-image-col-6 h1 {
    font-size: 5em;
  }
  .body-image-col-6 .line {
    top: -40px;
    width: 22em;
  }
  .body-image-col-6 img {
    top: -1.5em;
    width: 7em;
  }
  .n-items a {
    font-size: 0.95em;
    margin-right: -1px;
  }
  form input {
    height: 42px;
    width: 280px;
  }
  .div-form {
    top: 20px;
    left: -15em;
  }
}

@media (max-width: 991px) {
  .body-image-col-6 .line {
    top: -2em;
  }
  .body-image-col-6 img {
    top: -1em;
  }
  form input {
    height: 42px;
    width: 230px;
  }
  .div-form {
    top: 20px;
    left: -15em;
  }
}

@media (max-width: 767.98px) {
  .body-image-col-6 h1 {
    font-size: 3.5em;
  }
  .body-image-col-6 img {
    font-size: 2em;
    top: -20px;
  }
  .body-image-col-6 .line {
    top: -15px;
    width: 16em;
  }
}
@media (max-width: 575.98px) {
  .body-image-col-6 h1 {
    font-size: 2.5em;
  }
  .body-image-col-6 img {
    font-size: 1.5em;
    top: -20px;
  }
  .body-image-col-6 .line {
    top: -15px;
    width: 12em;
  }
}
@media (max-width: 320px) {
  .body-image-1 img {
    object-fit: cover;
    width: 200vw;
    height: auto;
  }
}
</style>
