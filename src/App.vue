<template>
  <navigation />
  <about />
  <skills class="mt-5" />
  <experience class="mt-5" />
  <education class="mt-5" />
  <projects class="mt-5" />
  <footer-component />
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import Navigation from './components/navigation.vue';
import About from './components/about.vue';
import Skills from './components/skills.vue';
import Experience from './components/experience.vue';
import Education from './components/education.vue';
import Projects from './components/projects.vue';
import FooterComponent from './components/footer.vue';

@Options({
  components: { Navigation, About, Skills, Experience, Education, Projects, FooterComponent },
})
export default class App extends Vue {}
</script>

<style>
@import '../node_modules/bootstrap/dist/css/bootstrap.min.css';
@import '../node_modules/font-awesome/css/font-awesome.min.css';
@import './timeline.css';

html {
  scroll-behavior: smooth;
}
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
  border-bottom: #4682b4 5px solid;
  padding-bottom: 9px;
  display: inline-block;
}
</style>
