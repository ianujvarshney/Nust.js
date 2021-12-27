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
            <!-- <b-nav-item-dropdown text="Lang" right>
                <b-dropdown-item href="#">EN</b-dropdown-item>
                <b-dropdown-item href="#">ES</b-dropdown-item>
                <b-dropdown-item href="#">RU</b-dropdown-item>
                <b-dropdown-item href="#">FA</b-dropdown-item>
              </b-nav-item-dropdown> -->
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
      <b-col col xl="6" class="body-image-2">
        <img
          src="@/pages/Home-Page/Images/body-image-2.png"
          alt="body-image-2"
        />
      </b-col>
      <b-col class="div-form">
        <form action="">
          <label>Asesoría Personalizada #SonrisaVejarano</label>
          <input type="text" />
          <input type="text" />
          <input type="text" />
          <input type="text" />
          <input type="text" />
          <input type="text" />
        </form>
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
  /* height: 40px; */
  /* width: 150px; */
  /* padding: 1px 0px 1px 0px; */
  text-align: center;
  border-radius: 5px;
  background-color: black;
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
  font-size: 1em;
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
.body-image-1 img {
  margin-top: 110px;
  width: 180%;
  height: auto;
}
.body-image-col-6 {
  margin-top: 140px;
  display: grid;
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
  width: 99vw;
  margin-left: -3px;
  height: auto;
  margin-top: -51px;
}
.div-form label {
  font-size: 2em;
  display: block;
  height: 100px;
  border: 1px solid white;
  background: white;
  color: black;
}
.div-form {
  border-radius: 5px;
  display: flex;
  position: relative;
  justify-content: center;
  text-align: center;
  top: 70px;
  left: -25em;
  border: 2px solid #fff;
  width: 4em;
  height: 50vh;
}
.div-form input {
  height: 50px;
  width: 340px;
  border-radius: 5px;
}

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
}

@media (max-width: 991px) {
  .body-image-col-6 .line {
    top: -2em;
  }
  .body-image-col-6 img {
    top: -1em;
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
