<template>
  <b-row class="container-fluid">
    <b-col>
      <b-row>
        <b-col>
          <h1>Estética Dental</h1>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <p>
            Llevamos a cabo técnicas estéticas y reconstructivas, orientadas al
            diseño de la sonrisa y función de los dientes. La estética dental es
            una especialidad de la odontología; soluciona problemas de salud
            dental relacionados con la armonía y estética de la boca, para
            lograr una sonrisa perfecta.
          </p>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <img src="@/pages/Home-Page/Images/slider.jpg" alt="" />
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <button>Contactar a un asesor</button>
        </b-col>
      </b-row>
    </b-col>
  </b-row>
</template>

<script>
export default {}
</script>

<style scoped>
* {
  padding: 0;
  margin: 0;
}
.container-fluid {
  height: 100vh;
  width: 100vw;
}
.container-fluid .col .row .col {
  margin: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.container-fluid .col .row:nth-child(4) .col:first-child button {
  width: 400px;
  height: 45px;
  background: #ffbe34 0% 0% no-repeat padding-box;
  border-radius: 5px;
  border: none;
}
</style>
