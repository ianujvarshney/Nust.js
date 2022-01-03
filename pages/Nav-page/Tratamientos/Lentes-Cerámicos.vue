<template>
  <b-row class="container">
    <b-row class="row-1"
      ><b-col>
        <h1>Marcela Vejarano</h1>
        <img src="" />
      </b-col>
    </b-row>
    <b-row class="row-2">
      <b-col class="row-2-col-1">
        <p>
          Realizando procedimientos con altos estándares de calidad que les
          permita mejorar su salud, estética dental y sonreír siempre.
        </p>
        <p>
          Vejarano Odontología Especializada, es una clínica fundada en el 2007
          por La Dra. Marcela Vejarano. Nuestropropósito es Hacerte sonreír
          siempre y para esto contamos con los mejores profesionales y
          necesiten, altamente capacitados para brindar atención integral en
          salud especialistas en cada área de la odontología que nuestros
          pacientes oral.
        </p>
        <p>
          Nuestras instalaciones disponen de equipos con la mejor tecnología
          para el apropiado diagnóstico y tratamiento de las diferentes
          patologías de nuestros pacientes, brindándoles un servicio cálido e
          integral. Somos un equipo humano comprometido a mejorar tu calidad de
          vida, ofreciéndote experiencias únicas en tu visita a nuestros
          consultorios
        </p>
      </b-col>
    </b-row>
    <b-row>
      <b-col>
        <button>Contactar a un asesor</button>
      </b-col>
    </b-row>
  </b-row>
</template>

<script>
export default {}
</script>

<style scoped>
* {
  padding: 0;
  margin: 0;
  /* box-sizing: border-box; */
}
.container {
  border: 1px solid rgb(41, 53, 165);
  height: 100vh;
  width: 100%;
}
.row-1 {
  display: flex;
  justify-content: center;
  align-items: center;
}
.row-2 {
  border: 1px solid red;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  flex-flow: row;
}
.row-2-col-1 {
  /* display: flex; */
}
</style>