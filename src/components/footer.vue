<template>
  <footer id="contact">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-xl-2 col-4 footer-link">
          <a href="https://github.com/Matii96" target="_blank" class="contact-link">
            <i class="fa fa-github fa-3x round" />
          </a>
        </div>
        <div class="col-xl-2 col-4 footer-link">
          <a href="https://medium.com/@matii96" target="_blank" class="contact-link">
            <i class="fa fa fa-medium fa-3x round" />
          </a>
        </div>
        <div class="col-xl-2 col-4 footer-link">
          <a href="mailto:mateusz.fonfara96@gmail.com" class="contact-link">
            <i class="fa fa-envelope fa-3x round" />
          </a>
        </div>
      </div>
    </div>
  </footer>
</template>

<script lang="ts">
import { Vue } from 'vue-class-component';

export default class Footer extends Vue {}
</script>

<style scoped>
footer {
  background-color: #383838;
}
a {
  color: #fff;
}
a:hover {
  color: #c8c8c8;
}
.container {
  padding-bottom: 80px;
}
.footer-link {
  padding-top: 80px;
  text-align: center;
}
</style>
