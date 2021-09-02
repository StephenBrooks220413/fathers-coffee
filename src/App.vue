<template>
  <nav class="fixed-top">
    <div id="nav1">
      <div class="w3-bar w3-black w3-border w3-card-4">
        <router-link to="/" class="w3-bar-item text-white w3-button"
          >Home</router-link
        >
        <router-link to="/about" class="w3-bar-item text-white w3-button"
          >About</router-link
        >
        <router-link to="/contact" class="w3-bar-item text-white w3-button"
          >Contact</router-link
        >
        <router-link to="/community" class="w3-bar-item text-white w3-button"
          >Community</router-link
        >
      </div>
    </div>
    <div id="nav2">
      <div class="w3-bar w3-black w3-border w3-card-4">
        <div class="w3-dropdown-hover">
          <button class="btn btn-dark btn-lg">MENU</button>
          <div class="w3-dropdown-content w3-bar-block w3-border">
            <router-link to="/" class="w3-bar-item text-dark w3-button"
              >Home</router-link
            >
            <router-link to="/about" class="w3-bar-item text-dark w3-button"
              >About</router-link
            >
            <router-link to="/contact" class="w3-bar-item text-dark w3-button"
              >Contact</router-link
            >
            <router-link to="/community" class="w3-bar-item text-dark w3-button"
              >Community</router-link
            >
          </div>
        </div>
      </div>
    </div>
  </nav>
  <router-view />
  <br />
  <footer class="bg-dark mt-5 text-center text-white">
    <!-- Grid container -->
    <div class="container p-4 pb-0">
      <!-- Section: Social media -->
      <section class="mb-4">
        <!-- Facebook -->
        <a
          class="btn btn-outline-light btn-floating m-1"
          href="#!"
          role="button"
          ><i class="fab fa-facebook-f"></i
        ></a>

        <!-- Twitter -->
        <a
          class="btn btn-outline-light btn-floating m-1"
          href="#!"
          role="button"
          ><i class="fab fa-twitter"></i
        ></a>

        <!-- Google -->
        <a
          class="btn btn-outline-light btn-floating m-1"
          href="#!"
          role="button"
          ><i class="fab fa-google"></i
        ></a>

        <!-- Instagram -->
        <a
          class="btn btn-outline-light btn-floating m-1"
          href="#!"
          role="button"
          ><i class="fab fa-instagram"></i
        ></a>

        <!-- Linkedin -->
        <a
          class="btn btn-outline-light btn-floating m-1"
          href="#!"
          role="button"
          ><i class="fab fa-linkedin-in"></i
        ></a>

        <!-- Github -->
        <a
          class="btn btn-outline-light btn-floating m-1"
          href="https://github.com/StephenBrooks220413/fathers-coffee.git"
          role="button"
          ><i class="fab fa-github"></i
        ></a>
      </section>
      <!-- Section: Social media -->
    </div>
    <!-- Grid container -->

    <!-- Copyright -->
    <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2)">
      © 2020 Copyright:
      <a class="text-white" href="https://mdbootstrap.com/"
        >Fathers&Coffee.com</a
      >
    </div>
    <!-- Copyright -->
  </footer>
</template>

<script>
import * as mdb from "mdb-ui-kit";

export default {
  mdb,
};
</script>

<style lang="scss">
@import "~mdb-ui-kit/css/mdb.min.css";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav1 {
  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
