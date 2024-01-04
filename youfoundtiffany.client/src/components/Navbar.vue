<template>
  <nav class="navbar navbar-dark bg-dark fixed-top glow">
    <div class="container-fluid">
      <a class="navbar-brand txt-Passion" href="#">Tiffany Hays</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasDarkNavbar"
        aria-controls="offcanvasDarkNavbar" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="offcanvas offcanvas-end text-bg-dark" tabindex="-1" id="offcanvasDarkNavbar"
        aria-labelledby="offcanvasDarkNavbarLabel">
        <div class="offcanvas-header">
          <h5 class="offcanvas-title" id="offcanvasDarkNavbarLabel">Off Canvas Label Here</h5>
          <button type="button" class="btn-close btn-close-white" data-bs-dismiss="offcanvas" aria-label="Close"></button>
        </div>
        <div class="offcanvas-body">
          <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">TrapprKeepr</a>
            </li>
            <!-- <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Dropdown
              </a>
              <ul class="dropdown-menu dropdown-menu-dark">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li>
                  <hr class="dropdown-divider">
                </li>
                <li><a class="dropdown-item" href="#">Something else here</a></li>
              </ul>
            </li> -->
          </ul>
          <!-- <form class="d-flex mt-3" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-success" type="submit">Search</button>
          </form> -->
        </div>
      </div>
    </div>
  </nav>

  <!-- OG NAVBAR -->
  <!-- <nav class="navbar navbar-expand-lg bg-SkyMist px-3">
  <router-link class="navbar-brand d-flex" :to="{ name: 'Home' }">
    <div class="d-flex flex-column align-items-center"> -->
  <!-- <img alt="logo" src="../assets/img/THLogoHorizontal.svg" height="200" /> -->
  <!-- </div>
      </router-link>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText"
      aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav me-auto">
        <li>
          <router-link :to="{ name: 'About Me' }" class="btn lighten-30 selectable font-Lato fw-bold">
            About Me
          </router-link>
        </li>
      </ul> -->
  <!-- TODO ADD LOGIN TO OFFCANVAS NAVBAR -->
  <!-- LOGIN COMPONENT HERE -->
  <!-- <Login />
      </div>
    </nav> -->
  <!-- OG NAVBAR -->
</template>

<script>
import Login from './Login.vue';
export default {
  setup() {
    return {}
  },
  // components: { Login }
}
</script>

<style scoped>
a:hover {
  text-decoration: none;
}



.navbar-nav .router-link-exact-active {
  border-bottom: 2px solid var(--bs-success);
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}

@media screen and (min-width: 768px) {
  nav {
    height: 64px;
  }
}
</style>
