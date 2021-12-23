<template>
  <v-container-fluid>
    <v-row>
      <v-col-12>
        <b-navbar class="navbar" toggleable="lg" type="light" variant="light">
          <b-navbar-brand class="mainlogo" href="#"
            ><img src="@/pages/Home-Page/Images/MainLogo.svg" /></b-navbar-brand>

          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
          <b-collapse id="nav-collapse" is-nav>
            <!-- <b-navbar-nav>
              <b-nav-item href="#">Link</b-nav-item>
              <b-nav-item href="#" disabled>Disabled</b-nav-item>
            </b-navbar-nav> -->

            <!-- Right aligned nav items -->
            <b-navbar-nav class="ml-auto">
                <b-nav-item class="n-items" href="#">Home</b-nav-item>
                <b-nav-item class="n-items" href="#">Dra. Marcela Vejarano</b-nav-item>
                <b-nav-item class="n-items" href="#">Tratamientos</b-nav-item>
                <b-nav-item class="n-items" href="#">Testimonios</b-nav-item>
                <b-nav-item class="n-items" href="#">Antes y Después</b-nav-item>
                <b-nav-item class="n-items headphone" href="#"><img src="@/pages/Home-Page/Images/headphonelogo.svg" alt="headphonelogo"><span>Contacto</span>
                </b-nav-item>
            </b-navbar-nav>
              <!-- <b-nav-item-dropdown text="Lang" right>
                <b-dropdown-item href="#">EN</b-dropdown-item>
                <b-dropdown-item href="#">ES</b-dropdown-item>
                <b-dropdown-item href="#">RU</b-dropdown-item>
                <b-dropdown-item href="#">FA</b-dropdown-item>
              </b-nav-item-dropdown> -->
            </b-navbar-nav>
          </b-collapse>
        </b-navbar></v-col-12>
    </v-row>
  </v-container-fluid>
</template>
<script setup lang="js">
import mainlogo from '@/pages/Home-Page/Images/MainLogo.svg';
export default {
  components:
  {
    mainlogo
  },
}
</script>
<style scoped>
*{
  color: none;
  padding:0;
  margin:0;
  box-sizing: border-box;
  }
  .headphone img{
    height: 15%;
    width:15%;
    /* margin: 2px; */
}
  .headphone span{
   color:white;
}
.headphone{
  padding: 5px 0px 5px 0px;
    text-align: center;
    border-radius: 5px;
    background-color: black;
  }
.mainlogo img{
    /* margin:5px; */
  margin-left: 100px;
  height: 90%;
  width: 70%;
  }
  .navbar{

    box-shadow: 0 10px 0 red; 
    height: 18vh;
    width: 100vw;
    }
    .navbar .ml-auto{
      margin-right:100px;    
    }
  .n-items{
    text-transform: capitalize;
      margin-right: 15px;
      font-weight: 500;
    } 
</style>
