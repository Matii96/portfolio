<template>
  <header class="sticky-top">
    <nav class="navbar navbar-expand-md navbar-light bg-light">
      <a class="navbar-brand">Mateusz Fonfara</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarCollapse"
        aria-controls="navbarCollapse"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-center" id="navbarCollapse">
        <ul class="navbar-nav">
          <li class="nav-item active">
            <a class="nav-link" href="#">ABOUT</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">SKILLS</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">EXPERIENCE</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">EDUCATION</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">PORTFOLIO</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">CONTACT</a>
          </li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script lang="ts">
import { Vue } from 'vue-class-component';

export default class Navigation extends Vue {}
</script>

<style scoped>
.nav-item {
  margin-left: 15px;
  margin-right: 15px;
}
.navbar-brand,
.nav-item {
  font-size: 24px;
  font-family: Copperplate, Copperplate Gothic Light, fantasy;
}

@media only screen and (min-width: 760px) {
  .navbar-brand {
    display: none;
  }
}
</style>
