<template>
  <b-container-fluid class="container-fluid">
    <b-row>
      <b-col col sm="12">
        <b-navbar
          col
          sm="12"
          class="navbar"
          toggleable="lg"
          type="light"
          variant="light"
        >
          <b-navbar-brand class="mainlogo" href="#"
            ><img src="@/pages/Home-Page/Images/MainLogo.svg"
          /></b-navbar-brand>

          <b-navbar-toggle target="nav-collapse">
            <img
              class="image-toggle-navbar"
              height="30px"
              width="30px"
              src="@/pages/Home-Page/Images/headphonelogo.svg"
              alt=""
            />
          </b-navbar-toggle>
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
              <b-nav-item class="n-items">
                <NuxtLink to="/Nav-page/Marcela-Vejarano">
                  Dra. Marcela Vejarano
                </NuxtLink>
              </b-nav-item>
              <!-- 
              <b-nav-item class="n-items"
                ><Nuxt-Link to="/Nav-page/Tratamientos">
                  Tratamientos
                </Nuxt-Link></b-nav-item
              > -->
              <b-nav-item-dropdown class="drop" text="Tratamientos">
                <b-dropdown-item href="/Nav-page/Tratamientos/Lentes-Cerámicos"
                  >Lentes Cerámicos
                </b-dropdown-item>
                <b-dropdown-item href="/Nav-page/Tratamientos/Diseño"
                  >Diseño de sonrisa</b-dropdown-item
                >
                <b-dropdown-item href="/Nav-page/Tratamientos/Estética"
                  >Estética Dental</b-dropdown-item
                >
                <b-dropdown-item href="/Nav-page/Tratamientos/Rehabilitación"
                  >Rehabilitación Oral</b-dropdown-item
                >
                <b-dropdown-item href="/Nav-page/Tratamientos/Implantología"
                  >Implantología</b-dropdown-item
                >
                <b-dropdown-item href="/Nav-page/Tratamientos/Ortodoncia"
                  >Ortodoncia</b-dropdown-item
                >
                <b-dropdown-item href="/Nav-page/Tratamientos/Blanqueamiento"
                  >Blanqueamiento Dental</b-dropdown-item
                >
                <b-dropdown-item href="/Nav-page/Tratamientos/Endodoncia"
                  >Endodoncia</b-dropdown-item
                >
                <b-dropdown-item href="/Nav-page/Tratamientos/Periodoncia"
                  >Periodoncia</b-dropdown-item
                >
              </b-nav-item-dropdown>
              <b-nav-item class="n-items"
                ><Nuxt-Link to="/Nav-page/Testimonios">
                  Testimonios
                </Nuxt-Link></b-nav-item
              >
              <b-nav-item class="n-items"
                ><Nuxt-Link to="/Nav-page/Antesy-Después">
                  Antes y Después
                </Nuxt-Link></b-nav-item
              >
              <b-nav-item class="n-items headphone">
                <img
                  href="/Nav-page/Contact"
                  src="@/pages/Home-Page/Images/headphonelogo.svg"
                  alt="headphonelogo"
                />Contacto
              </b-nav-item>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar></b-col
      >
    </b-row>
    <b-row class="row-row">
      <b-col col lg="6" md="6" xl="6" class="body-image-1">
        <img src="@/pages/Home-Page/Images/sonrisa.jpg" alt="body-image" />
      </b-col>
      <b-col col sm="6" lg="6" md="6" xl="6" class="body-image-col-6">
        <h1 class="text-center">Lentes Cerámicos</h1>
        <div class="line"></div>
        <img src="@/pages/Home-Page/Images/Group.svg" alt="svg" />
      </b-col>
    </b-row>
    <b-row class="background-color-white">
      <b-col>
        <b-row>
          <b-col cols="6" class="body-image-2">
            <img
              src="@/pages/Home-Page/Images/body-image-2.png"
              alt="body-image-2"
            />
          </b-col>
          <b-col cols="6" class="col-div-form">
            <div class="div-form">
              <h1
                class="h1-lentus-div"
                style="
                  color: rgb(255, 255, 255);
                  /* position: absolute; */
                  top: 0;
                  margin: -300px 0 0;
                  font-size: 83px;
                  font-weight: 700;
                  font-family: 'Playfair Display';
                "
              >
                Lentes Cerámicos
              </h1>
              <div class="div-line h1-lentus-div"></div>
              <img
                class="h1-lentus-div"
                data-v-f77b107c=""
                src="/_nuxt/pages/Home-Page/Images/Group.svg"
                alt=""
                style="color: whitye; color: white; width: 365px"
              />
              <form action="">
                <label
                  ><span>Asesoría Personalizada </span> #SonrisaVejarano</label
                >
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
        <b-row class="h1-row-col-1">
          <b-col class="h1-text-col-1">
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
                <button><i class="fas fa-play"></i>Ver</button>
              </div>
            </div>
            <div class="div-1">
              <div class="div-2">
                <img src="@/pages/Home-Page/Images/Image-4.jpg" />
              </div>
              <div class="div-3">
                <p>Lorem ipsum</p>
                <button><i class="fas fa-play"></i>Ver</button>
              </div>
            </div>
            <div class="div-1">
              <div class="div-2">
                <img src="@/pages/Home-Page/Images/Image-4.jpg" />
              </div>
              <div class="div-3">
                <p>Lorem ipsum</p>
                <button><i class="fas fa-play"></i>Ver</button>
              </div>
            </div>
            <div class="div-1">
              <div class="div-2">
                <img src="@/pages/Home-Page/Images/Image-4.jpg" />
              </div>
              <div class="div-3">
                <p>Lorem ipsum</p>
                <button><i class="fas fa-play"></i>Ver</button>
              </div>
            </div>
          </b-col>
        </b-row>
        <b-row class="b-row-9">
          <b-col class="b1" cols="2">
            <div class="text-center"></div>
            <div class="text-center"></div>
            <div class="text-center"></div>
          </b-col>
        </b-row>
        <b-row>
          <b-col>
            <div class="text-center h1-second-div">
              <h1 class="h1-second-part">Cambios Fabulosos</h1>
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
                <img
                  src="@/pages/Home-Page/Images/Teeth/5.svg"
                  alt="Ortodoncia"
                />
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
                <img
                  src="@/pages/Home-Page/Images/Teeth/8.svg"
                  alt="Endodoncia"
                />
                <p>Endodoncia</p>
              </div>
            </div>
            <div class="a1">
              <div>
                <img
                  src="@/pages/Home-Page/Images/Teeth/9.svg"
                  alt="Periodoncia"
                />
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

        <b-row class="b-row-9">
          <b-col class="b1" cols="2">
            <div class="text-center"></div>
            <div class="text-center"></div>
            <div class="text-center"></div>
          </b-col>
        </b-row>
        <b-row class="text-center b-row-5">
          <b-col class="b-col-5">
            <img src="@/pages/Home-Page/Images/10.svg" alt="" />
          </b-col>
        </b-row>
        <b-row>
          <b-col class="h1-text-col">
            <h1 class="text-center h1-text">Asesoría Online</h1>
          </b-col>
        </b-row>
        <b-row class="b-row-6">
          <b-col cols="3" class="b-row-col-6">
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
        </b-row>
      </b-col>
    </b-row>
    <b-row class="b-row-8">
      <b-col cols="5" class="footer text-center">
        <div>
          <img src="@/pages/Home-Page/Images/Mainlogo2.png" alt="Mainlogo" />
        </div>
        <div class="new">
          <p>
            <i class="fas fa-map-marker-alt"></i>Cra 14 # 81-19 Consultorio 203
          </p>
          <p><i class="fas fa-mobile-alt"></i>320 8037031</p>
          <p><i class="fas fa-envelope"></i>info@odontologiavejarano.com</p>
        </div>
        <div class="new1">
          <p>
            Marcela Vejarano © All Rights Reserved 2021. Digital Strategy By
            Closer Design Networks
          </p>
        </div>
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
.h1-lentus-div {
  display: none;
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
.image-toggle-navbar[data-v-f77b107c] {
  background: #000;
  font-size: 30px;
  border-radius: 20px;
  padding: 5px;
  /* position: relative; */
  /* left: 145vw;
  top: -45px; */
}

.navbar-light .navbar-nav .nav-link:hover,
.navbar-light .navbar-nav .nav-link:focus {
  color: black;
  outline: none;
}
.navbar-light {
  color: rgba(0, 0, 0, 0.5);
  border-color: none;
}
.n-items a {
  font-size: 17px;
  font-weight: 600;
  text-decoration: none;
  text-transform: capitalize;
  margin-right: 15px;
  font-weight: 500;
  color: black;
  transition: 1s;
}

.n-items a:hover,
a.active {
  color: #ffbe34;
  /* font-weight: 800; */
}
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
.headphone[data-v-f77b107c] .nav-link {
  background-color: #000;
  padding: 5px 0;
  font-weight: bold;
  color: #fff;
  display: inline-block;
  margin: 0;
  text-align: center;
  border-radius: 4px;
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
  left: -30em;
  width: -14em !important;
  height: 50vh;
  width: 59em;
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
  width: 450px;
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
.h1-text-col {
  height: 150px;
}
.h1-row-col-1 {
  margin-top: 50px;
  justify-content: center;
  align-items: center;
  height: 200px;
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
  width: 32em;
  background: #efefef;
  border-radius: 10px;
  padding: 7px;
  margin: 5px;
}
.b-col-2 .div-3 {
  width: 15em;
  height: 12em;
}
.b-row-2 {
  justify-content: center;
}
.b-col-2 .div-3 button {
  margin-top: 20px;
  margin-left: 10px;
  width: 220px;
  border: none;
  height: 60px;
  font-size: 22px;
  font-weight: 500;
  background: var(--unnamed-color-ffffff) 0% 0% no-repeat padding-box;
  background: #ffffff 0% 0% no-repeat padding-box;
  box-shadow: 0px 2px 2px #0000000f;
  border-radius: 5px;
  opacity: 1;
}
.b-col-2 .div-3 button i {
  font-size: 25px;
  margin-right: 20px;
}
.b-col-2 .div-3 p {
  width: 208px;
  height: 46px;
  font-size: 30px;
  font-weight: 600;
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
  margin-bottom: 50px;
}

.h1-second {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100px;
  margin-top: 50px;
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
  color: #000000;
  text-align: center;
  font-size: 18px;
  font-weight: 600;
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

.b-col-3 .a1-change:nth-child(10) div img {
  margin-left: 3em;
}
.b-col-3 .a1-change:nth-child(10) div p {
  text-align: center;
  width: 10em;
  font-size: 18px;
  font-weight: 600;
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
.b-row-5 {
  height: 200px;
  align-items: center;
}
.b-row-5 .b-col-5 img {
  max-width: 150px;
}

.b-row-6 {
  justify-content: center;
  align-items: center;
  height: 100px;
  width: 100%;
}
.h2-text {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 430px;
  height: 87px;
  font-weight: 900;
  color: #000000;
  background: #ffbe34 0% 0% no-repeat padding-box;
  border-radius: 5px;
}
.b-row-7 {
  display: flex;
  justify-content: center;
  align-items: center;
}
.b-col-7 {
  display: flex;
  height: 20vh;
  /* margin-bottom: 30px; */
  justify-content: center;
  align-items: center;
}
.b-col-7 div {
  width: 4.5vw;
  display: flex;
  justify-content: space-evenly;
}
.b-col-7 a img {
  height: 60px;
  width: 60px;
}
.b-row-8 {
  display: flex;
  justify-content: center;
  height: 50vh;
  background: #000000;
}
.b-row-8 .footer div {
  height: 20vh;
}
.b-row-8 .footer div.new p {
  position: relative;
  top: 50px;
  left: 250px;
  text-align: left;
  width: 15vw;
  color: #fff;
  font-size: 14px;
}
.b-row-8 .footer div.new i {
  color: #ffbe34;
  margin: 5px;
}
.new1 {
  height: 20px !important;
  width: 45vw;
  color: var(--unnamed-color-ffffff);
  text-align: center;
  font: normal normal normal 12px/120px Outfit;
  letter-spacing: 0px;
  color: #ffffff;
  opacity: 1;
}
.footer:first-child img {
  max-width: 280px;
  position: relative;
  top: 50px;
}
.b-row-9 {
  justify-content: center;
  height: 140px;
}
.b-row-9 .b1 {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.b-row-9 .b1 div:nth-child(1) {
  height: 25px;
  width: 25px;
  border-radius: 15px;
  background: #ffbe34;
  box-shadow: 0 0 10px #ffbe34;
}
.b-row-9 .b1 div:nth-child(2) {
  height: 20px;
  width: 20px;
  border-radius: 15px;
  background: #000000;
}
.b-row-9 .b1 div:nth-child(3) {
  height: 20px;
  width: 20px;
  border-radius: 15px;
  background: #000000;
}

/******************************************************* MEDIA QUEARY ******************************************************** */
@media (max-width: 1024px) {
  .body-image-col-6 h1 {
    font-size: 6em;
  }

  .h1-lentus-div {
    display: none;
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

  .h1-lentus-div {
    display: none;
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
    left: -28em;
    width: 50em;
  }
  .h1-text[data-v-f77b107c] {
    font: normal normal bold 90px/129px Playfair Display;
  }
  .b-col-2 .div-1[data-v-f77b107c] {
    width: 29em;
  }
  .b-col-2 .div-3 p[data-v-f77b107c] {
    font-size: 23px;
    margin-top: 17px;
  }
  .b-col-2 .div-3 button[data-v-f77b107c] {
    width: 188px;
    height: 56px;
  }
  .h1-second[data-v-f77b107c] {
    font: normal normal bold 85px/119px Playfair Display;
    margin-bottom: 27px;
    margin-top: 91px;
  }
  .b-col-3 .a1[data-v-f77b107c] {
    width: 166px;
    margin: 5px;
    height: 203px;
  }
  .col-4-div .a2 img[data-v-f77b107c] {
    width: 305px;
    height: 201px;
    opacity: 1;
  }
  .b-row-5 .b-col-5 img[data-v-f77b107c] {
    max-width: 138px;
  }
  .a1-change[data-v-f77b107c] {
    height: 210px;
    width: 185px;
  }
}

@media (max-width: 1199px) {
  .body-image-col-6 h1 {
    font-size: 5em;
  }

  .h1-lentus-div {
    display: none;
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
    width: 300px;
  }
  .div-form {
    top: 20px;
    left: -23em;
    width: 45em;
  }
  .h1-text[data-v-f77b107c][data-v-f77b107c] {
    font: normal normal bold 75px/125xpx Playfair Display;
  }
  .b-col-2 .div-1[data-v-f77b107c][data-v-f77b107c] {
    width: 24em;
  }
  .b-col-2 .div-3 button[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    width: 161px;
    height: 46px;
  }
  .b-col-2 .div-1 .div-2 img[data-v-f77b107c] {
    height: 143px;
    width: 189px;
  }
  .h1-second-div[data-v-f77b107c] {
    height: 105px;
  }
  .h1-second[data-v-f77b107c][data-v-f77b107c] {
    font: normal normal bold 75px / 119px Playfair Display;
    margin-bottom: 35px;
    margin-top: 57px;
  }
  .b-col-3 .a1 div img[data-v-f77b107c] {
    margin-left: 10px;
    margin-bottom: 15px;
    width: 93px;
    height: 88px;
    opacity: 1;
  }
  .b-col-3 .a1[data-v-f77b107c][data-v-f77b107c] {
    width: 142px;
    margin: 5px;
    height: 182px;
  }
  .a1-change[data-v-f77b107c][data-v-f77b107c] {
    height: 186px;
    width: 159px;
  }
  .col-4-div .a2 img[data-v-f77b107c][data-v-f77b107c] {
    width: 251px;
    height: 169px;
  }
  .b-row-5 .b-col-5 img[data-v-f77b107c][data-v-f77b107c] {
    max-width: 123px;
  }
  .h1-text[data-v-f77b107c][data-v-f77b107c] {
    font: normal normal bold 66px / 129px Playfair Display;
  }
  .b-row-6[data-v-f77b107c] {
    justify-content: center;
    align-items: center;
    height: 87px;
    width: 64em;
  }
  .b-col-7 a img[data-v-f77b107c] {
    height: 50px;
    width: 50px;
  }
  .b-row-8 .footer div.new p[data-v-f77b107c] {
    width: 20vw;
  }
  .b-row-8 .footer div.new p[data-v-f77b107c] {
    left: 175px;
  }
}

@media (max-width: 991px) {
  /* ---------------------------------------NAVBAR------------------------------------------- */
  .ml-auto,
  .mx-auto {
    margin-left: auto !important;
    background: #fff;
    text-align: center;
  }

  .h1-lentus-div {
    display: none;
  }
  .navbar .ml-auto[data-v-f77b107c] {
    margin-top: 0px;
    margin-right: 0px;
  }
  .n-items a[data-v-f77b107c] {
    font-size: 22px;
    margin: 20px;
  }

  .body-image-col-6 .line {
    top: -2em;
  }
  .body-image-col-6 img {
    top: -1em;
  }
  form input {
    height: 42px;
    width: 280px;
  }
  .div-form {
    top: -10px;
    left: -20em;
    width: 30em;
  }
  form input {
    height: 35px;
    width: 220px;
  }
  .div-form label span[data-v-f77b107c] {
    text-align: center;
    margin-left: 37px;
    margin-right: 0px;
    font-weight: 600;
    font-size: 28px;
    width: 213px;
  }
  .h1-text[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    font: normal normal bold 56px / 129px Playfair Display;
  }
  .b-row-2 {
    display: flex;
    height: 60vh;
  }
  .b-col-2 .div-1 {
    height: 200px;
  }
  .b-col-2 .div-3 p[data-v-f77b107c] {
    width: 142 px;
    height: 55 px;
    font-size: 26px;
  }
  .b-col-2 .div-1[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    width: 20em;
    height: 30vh;
  }

  .b-row-3[data-v-f77b107c] {
    height: 130vh;
  }
  .a1-change[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    height: 180px;
    width: 143px;
  }
  .h1-second[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    font: normal normal bold 55px / 119px Playfair Display;
  }
  .col-4-div .a2 img[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    width: 213px;
    height: 155px;
  }
  .h2-text[data-v-f77b107c] {
    width: 343px;
    height: 84px;
  }
  .b-row-6[data-v-f77b107c][data-v-f77b107c] {
    height: 87px;
    width: 51em;
  }
  .b-col-7 a img[data-v-f77b107c][data-v-f77b107c] {
    height: 40px;
    width: 40px;
  }
  .b-col-2
    .div-3
    button[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    width: 107px;
    height: 43px;
    margin-top: 27px;
  }
  .b-col-2 .div-3 p[data-v-f77b107c][data-v-f77b107c] {
    font-size: 22px;
    width: 130px;
    height: 46px;
  }
  .b-row-8 .footer div.new p[data-v-f77b107c][data-v-f77b107c] {
    width: 24vw;
  }
  .b-row-8 .footer div.new p[data-v-f77b107c][data-v-f77b107c] {
    left: 143px;
  }
  .div-form label span[data-v-f77b107c][data-v-f77b107c] {
    text-align: center;
    font-size: 18px;
  }
  .h1-second-div[data-v-f77b107c][data-v-f77b107c] {
    height: 29px;
    margin-bottom: 0px;
  }
  .div-form label span[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    text-align: center;
    font-size: 16px;
  }
  .div-form label[data-v-f77b107c] {
    font-size: 1em;
    height: 76px;
  }
  .div-form[data-v-f77b107c] {
    top: 15px;
    left: -18em;
    width: 32em;
  }
}

@media (max-width: 767.98px) {
  .body-image-col-6 h1 {
    font-size: 3.5em;
  }

  .h1-lentus-div {
    display: none;
  }
  .body-image-col-6 img {
    font-size: 2em;
    top: -20px;
  }
  .body-image-col-6 .line {
    top: -15px;
    width: 16em;
  }
  .div-form {
    /* top: 15px; */
    /* left: -20em; */
    width: 38em;
    height: 10em;
  }
  .div-form label[data-v-f77b107c] {
    display: flex;
    font-size: 1.5em;
    height: 68px;
    align-content: center;
    align-items: center;
    background: white;
    color: black;
  }
  .div-form label span[data-v-f77b107c] {
    text-align: center;
    margin-left: 40px;
    margin-right: 20px;
    font-weight: 600;
  }
  .div-form label[data-v-f77b107c][data-v-f77b107c] {
    display: flex;
    font-size: 1.5em;
    height: 68px;
    align-content: center;
    align-items: center;
    background: white;
    color: black;
  }
  .div-form[data-v-f77b107c][data-v-f77b107c] {
    top: -1px;
    left: -16em;
  }
  .h1-text[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    font: normal normal bold 46px/129px Playfair Display;
  }
  .h1-row-col-1[data-v-f77b107c] {
    margin-top: -8px;
    justify-content: center;
    align-items: center;
    height: 159px;
  }
  .b-col-2
    .div-1[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    width: 100%;
  }
  .b-col-2
    .div-3
    button[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    width: 225px;
    height: 56px;
    margin-top: 27px;
  }
  .b-col-2 .div-3 p[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    font-size: 30px;
    width: 253px;
    height: 46px;
  }
  .b-col-2 .div-1 .div-2 img[data-v-f77b107c][data-v-f77b107c] {
    height: 154px;
    width: 245px;
  }
  .b-row-2[data-v-f77b107c] {
    height: 125vh;
  }
  .b-row-9 .b1 div[data-v-f77b107c]:nth-child(1) {
    height: 15px;
    width: 15px;
  }
  .b-row-3[data-v-f77b107c][data-v-f77b107c] {
    height: 149vh;
    display: flex;
    flex-wrap: wrap;
    flex-flow: column;
  }
  .b-row-5 .b-col-5 img[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    max-width: 106px;
  }

  .b-col-7 a img[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    height: 30px;
    width: 30px;
  }
  .h2-text[data-v-f77b107c][data-v-f77b107c] {
    width: 318px;
    height: 68px;
  }
  .col-3 .h2-text {
    font-size: 1;
  }
  .col-3 {
    flex: 0 0 25%;
    max-width: 41%;
  }
  .b-row-6 {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 10vw;
  }
  .b-row-6 .b-row-col-6 .h2-text {
    font-size: 2em;
  }
  .a1-change[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    height: 159px;
    width: 137px;
  }
  .h1-second[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    font: normal normal bold 43px / 119px Playfair Display;
  }
  .b-row-6[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    height: 87px;
    width: 47em;
  }
  .footer:first-child img[data-v-f77b107c] {
    max-width: 220 px;
  }
  .b-row-8
    .footer
    div.new
    p[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    width: 32vw;
  }
  .b-row-8
    .footer
    div.new
    p[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    left: 107px;
  }
  .new1[data-v-f77b107c] {
    height: 20px !important;
    width: 45vw;
    color: var(--unnamed-color-ffffff);
    text-align: center;
    font: normal normal normal 8px / 80px Outfit;
    letter-spacing: 0px;
    color: #ffffff;
    opacity: 1;
  }
}
@media (max-width: 575.98px) {
  .body-image-col-6 h1 {
    font-size: 2.5em;
  }
  .image-toggle-navbar[data-v-f77b107c][data-v-f77b107c] {
    position: relative;
    left: -9vw;
  }
  .image-toggle-navbar[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    position: relative;
    left: 88vw;
    top: -53px;
  }

  .h1-lentus-div {
    display: none;
  }
  .div-form
    label[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    display: table-footer-group;
    font-size: 26px;
    height: 102px;
    align-content: center;
    align-items: center;
    background: white;
    color: black;
  }
  .div-form
    label
    span[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    text-align: center;
    font-size: 36px;
  }
  .body-image-col-6 img {
    font-size: 1.5em;
    top: -20px;
  }
  .body-image-col-6 .line {
    top: -15px;
    width: 12em;
  }
  .col-div-form .div-form {
    display: block;
    width: 200%;
    height: 400px;
  }
  .col-div-form .div-form input {
    display: block;
    width: 90%;
  }
  .b-row-6[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    height: 80px;
    width: 26em;
  }
  .body-image-2 img[data-v-f77b107c] {
    height: 100vw;
    width: 102vw;
    margin-top: -52px;
    margin-left: -4px;
  }
  .div-form[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    top: 43px;
    left: -18em;
  }
  .body-image-2 img[data-v-f77b107c][data-v-f77b107c] {
    height: 100vw;
    width: 102vw;
    margin-top: -50px;
    margin-left: -4px;
  }
  .div-form label[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    display: flex;
    font-size: 2.5em;
    height: 102px;
    align-content: center;
    align-items: center;
    background: white;
    color: black;
  }
  .col-div-form .div-form input[data-v-f77b107c] {
    display: block;
    width: 99%;
  }
  form input[data-v-f77b107c] {
    height: 53px;
    width: 220px;
  }
  .body-image-2 img[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    height: 100vw;
    width: 100vw;
    margin-top: -50px;
    margin-left: 3px;
  }
  .body-image-2
    img[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    height: 109vw;
    width: 100vw;
    margin-top: -50px;
    margin-left: 3px;
  }
  .h1-text[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    font: normal normal bold 50px / 129px Playfair Display;
  }
  .div-form
    label
    span[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    text-align: center;
    font-size: 25px;
  }
  .b-row-3[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    height: 189vh;
    display: flex;
    flex-wrap: wrap;
    flex-flow: column;
  }
  .b-row-9[data-v-f77b107c] {
    justify-content: center;
    height: 581px;
  }
  .footer:first-child img[data-v-f77b107c] {
    max-width: 220 px;
    position: relative;
    top: 40px;
  }

  .b-row-8 .footer div[data-v-f77b107c] {
    height: 11vh;
  }
  .b-row-8
    .footer
    div.new
    p[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    width: 41vw;
  }
  .b-row-8
    .footer
    div.new
    p[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    left: 50px;
  }
  .b-col-2
    .div-1[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    width: 132%;
  }
  .new1[data-v-f77b107c][data-v-f77b107c] {
    height: 20px !important;
    width: 45vw;
    color: var(--unnamed-color-ffffff);
    text-align: center;
    display: flex;
    flex-flow: column;
    font: normal normal normal 6px / 155px Outfit;
    letter-spacing: 0px;
    color: #ffffff;
    opacity: 1;
  }
}
@media (max-width: 320px) {
  .row-row[data-v-f77b107c] {
    display: flex;
    flex-wrap: wrap;
    flex-flow: column;
    overflow: hidden;
    position: fixed;
  }
  .headphone[data-v-f77b107c] {
    border-radius: 5px;
    background-color: black;
    height: 34px;
    width: 0vw;
    display: block;
  }
  .image-toggle-navbar[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    position: relative;
    left: 145vw;
    top: -40px;
  }
  .body-image-1 img[data-v-f77b107c][data-v-f77b107c] {
    width: 330vw;
    margin-left: -148px;
  }
  .body-image-2
    img[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    height: 109vw;
    margin-top: 150vw;
  }
  .n-items a[data-v-f77b107c][data-v-f77b107c] {
    font-size: 22px;
    margin: 20px;
    display: block;
    width: 148vw;
    margin-top: 11px;
  }
  .navbar[data-v-f77b107c] {
    position: fixed;
    height: 18vh;
    z-index: 1;
    box-shadow: 0px 4px 4px rgb(0 0 0 / 25%);
  }
  .navbar[data-v-f77b107c][data-v-f77b107c] {
    width: auto;
  }
  .col-6 {
    flex: 0 0 50%;
  }
  .row {
    display: contents;
    flex-wrap: wrap;
    margin-right: -15px;
    margin-left: -15px;
  }
  .body-image-1 img[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    width: 517vw;
    margin-left: -241px;
  }
  .body-image-2
    img[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    height: 254vw;
    margin-top: 100vh;
    width: 160vw;
  }
  .div-form[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    top: -555px;
    left: 4em;
    display: block;
  }
  .col-div-form .div-form input[data-v-f77b107c][data-v-f77b107c] {
    width: 98%;
  }
  .div-form
    label[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    font-size: 20px;
  }
  form[data-v-f77b107c] {
    border-radius: 12px;
  }
  .col-6 {
    max-width: 60%;
  }
  .body-image-col-6 h1[data-v-f77b107c] {
    font-size: 3.6em;
    position: absolute;
    top: -5em;
    left: 20px;
    color: #fff;
  }
  .h1-row-col-1 {
    justify-content: center;
    align-items: center;
    height: 99 vh;
    background: #fff !important;
    margin-left: -69 px;
    margin-right: -161 px;
    width: 174 vw;
    margin-bottom: 139 px;
  }
  .h1-text[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    font: normal normal bold 96px / 129px Playfair Display;
  }
  .h1-text-col-1.col {
    margin-left: 63px;
  }
  .b-col-2
    .div-3
    button[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    width: 135px;
    height: 42px;
    margin-top: 26px;
    margin-left: 50px;
  }
  .b-col-2
    .div-3
    p[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    font-size: 24px;
    width: 202px;
    height: 46px;
  }
  .b-col-2
    .div-1[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    width: 215%;
    margin-left: 99vw;
  }
  .h1-second-div[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    height: 182vh;
    margin-bottom: 0px;
  }

  .b-row-3[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    height: 209vh;
    display: flex;
    flex-flow: column;
    width: 154vw;
  }
  .h1-second[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    font: normal normal bold 43px / 73px Playfair Display;
    margin-left: 38px;
    flex-wrap: wrap;
    flex-flow: column;
    display: flex;
  }
  .b-row-4 {
    margin-left: 194px;
    margin-top: 16px;
    display: block;
  }
  .col-4-div
    .a2
    img[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    width: 443px;
    height: 282px;
  }
  .col-4-div[data-v-f77b107c] {
    height: 160vh;
  }
  .b-row-5
    .b-col-5
    img[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    max-width: 109px;
    display: flex;
    justify-content: center;
    margin-left: 205px;
    margin-top: 40px;
  }
  .h1-text-col[data-v-f77b107c] {
    height: 150px;
    margin-left: 67px;
    margin-top: 97px;
  }
  .h1-text-col[data-v-f77b107c][data-v-f77b107c] {
    height: 331px;
    margin-left: 80px;
    margin-top: 111px;
  }
  .h2-text[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    width: 479px;
    height: 68px;
    margin-left: 31px;
  }
  .b-col-7 div[data-v-f77b107c] {
    width: 73px;
  }
  .b-col-7
    a
    img[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    height: 60px;
    width: 60px;
    margin: 20px;
  }
  .col-3[data-v-f77b107c] {
    flex: 0 0 25%;
    max-width: 144%;
    width: 139%;
  }
  .b-row-8 .footer div[data-v-f77b107c][data-v-f77b107c] {
    height: 20vh;
    background: #000;
    width: 513px;
  }
  .b-row-8
    .footer
    div.new
    p[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    left: 136px;
  }

  .b-row-8
    .footer
    div.new
    p[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    width: 95vw;
  }
  .b-col-3 .a1[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    width: 143px;
    height: 196px;
  }
  .a1-change[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    height: 202px;
    width: 137px;
  }

  .mainlogo img[data-v-f77b107c] {
    margin-left: 100px;
    height: 90%;
    width: 55%;
  }
  .navbar-light .navbar-toggler-icon {
    /* background-image: url('@/pages/Home-Page/Images/headphonelogo.svg'); */
    max-width: 5px;
    background: #000;
    border: 10px solid red;
  }
  .new1[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    height: 152px !important;
    width: 45vw;
    color: var(--unnamed-color-ffffff);
    text-align: center;
    display: flex;
    flex-flow: column;
    padding: 20px;
    font: normal normal normal 20px / 30px Outfit;
    letter-spacing: 0px;
    color: #fff;
    opacity: 1;
    background: black;
  }
  .div-form
    label
    span[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    text-align: center;
    font-size: 26px;
    width: 303px;
  }
  .div-form
    label[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    display: flex;
    font-size: 1.2em;
    height: 102px;
    align-content: center;
    align-items: center;
    background: white;
    color: black;
    flex-wrap: wrap;
    justify-content: center;
  }
  .h1-text[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    font: normal normal bold 98px / 129px Playfair Display;
    margin-bottom: 74px;
  }
  .body-image-col-6 h1[data-v-f77b107c][data-v-f77b107c] {
    display: none;
  }

  .h1-lentus-div {
    display: block;
  }
  .div-line {
    border: 1px solid #ffbe34;
  }
  .b-row-9 .b1[data-v-f77b107c] {
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: relative;
    top: 96vh;
    left: 72vw;
  }
  .background-color-white {
    background: #fff;
    display: block;
  }
  .h1-second-part[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    font: normal normal bold 76px / 80px Playfair Display;
    margin-left: 160px;
    flex-wrap: wrap;
    flex-flow: column;
    display: flex;
    margin-top: 430px;
  }
  .h1-second[data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c][data-v-f77b107c] {
    font: normal normal bold 55px / 73px Playfair Display;
    margin-left: 90px;
  }
}
</style>
