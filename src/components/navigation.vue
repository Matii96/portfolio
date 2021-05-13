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
          <li class="nav-item">
            <a class="nav-link" href="#about">ABOUT</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#skills">SKILLS</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#experience">EXPERIENCE</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#education">EDUCATION</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#projects">PROJECTS</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">CONTACT & LINKS</a>
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
  font-size: 22px;
  font-family: 'Helvetica Neue', Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';
  font-weight: 600;
}

@media only screen and (min-width: 760px) {
  .navbar-brand {
    display: none;
  }
}
</style>
