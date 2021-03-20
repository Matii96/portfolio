<template>
  <navigation />
  <about />
  <skills class="mt-5" />

  <div class="mb-5" />
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import Navigation from './components/navigation.vue';
import About from './components/about.vue';
import Skills from './components/skills.vue';

@Options({
  components: { Navigation, About, Skills },
})
export default class App extends Vue {}
</script>

<style>
@import '../node_modules/bootstrap/dist/css/bootstrap.min.css';
@import '../node_modules/font-awesome/css/font-awesome.min.css';

body {
  font-family: 'Open Sans', sans-serif;
}
.title {
  font-family: 'Open Sans', sans-serif;
  font-size: 36px;
  line-height: 38px;
  padding-bottom: 0px;
  font-weight: 400;
  text-transform: uppercase;
  margin: 0;
  border-bottom: #4682b4 6px solid;
  padding-bottom: 9px;
  display: inline-block;
}
/* .modal {
  display: block;
}
.modal.show {
  background-color: rgba(0, 0, 0, 0.6);
} */
</style>
