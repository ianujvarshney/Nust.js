<template>
  <div>
    <div>
      <b-avatar variant="secondary"></b-avatar>
      <b-avatar variant="primary"></b-avatar>
      <b-avatar variant="dark"></b-avatar>
      <b-avatar variant="light"></b-avatar>
      <b-avatar variant="success"></b-avatar>
      <b-avatar variant="danger"></b-avatar>
      <b-avatar variant="warning"></b-avatar>
      <b-avatar variant="info"></b-avatar>
    </div>
    <section>
      <div class="mb-2">
        <b-avatar src="https://placekitten.com/300/300"></b-avatar>
        <b-avatar src="https://placekitten.com/300/300" size="6rem"></b-avatar>
      </div>
    </section>
    <section>
      <nav class="navbar navbar-expand-xl navbar-dark bg-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Navbar</a>
          <button
            class="navbar-toggler d-lg-none"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#collapsibleNavId"
            aria-controls="collapsibleNavId"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="collapsibleNavId">
            <ul class="navbar-nav me-auto mt-2 mt-lg-0">
              <li class="nav-item active">
                <a class="nav-link" href="#">
                  <span class="visually-hidden">(current)</span>
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#"
                  id="dropdownId"
                  data-bs-toggle="dropdown"
                  aria-haspopup="true"
                  aria-expanded="false"
                  >Dropdown</a
                >
                <div class="dropdown-menu" aria-labelledby="dropdownId">
                  <a class="dropdown-item" href="#">Action 1</a>
                  <a class="dropdown-item" href="#">Action 2</a>
                </div>
              </li>
            </ul>
            <form class="d-flex my-2 my-lg-0">
              <input
                class="form-control me-sm-2"
                type="text"
                placeholder="Search"
              />
              <button
                class="btn btn-outline-success my-2 my-sm-0"
                type="submit"
              >
                Search
              </button>
            </form>
          </div>
        </div>
      </nav>
    </section>
    <h1 class="text-center">Nuxt.js</h1>
  </div>
</template>
<script>
export default {
  data() {
    return {
      slide: 0,
      sliding: null,
    }
  },
  methods: {
    onSlideStart(slide) {
      this.sliding = true
    },
    onSlideEnd(slide) {
      this.sliding = false
    },
  },
}
</script>

<style>
h1 {
  font-size: 120px;
  color: blue;
}
</style>
