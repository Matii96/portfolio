<template>
  <section id="projects">
    <div class="container pt-5 pb-5">
      <div class="text-center"><h2 class="title">PROJECTS</h2></div>

      <div class="row justify-content-center mt-5">
        <div class="col-xl-4 col-md-6 mt-3">
          <div class="card">
            <h3 class="card-header">Context chatbot</h3>
            <div class="card-body">
              My engineering thesis. The aim of this project was to create chatbot that can move through conversation
              tree, defined in JSON file, with accepting user input. Example would be:
              <span style="color: red">Give me</span> <span style="color: green"> two</span>
              <span style="color: blue"> bottles of water</span>.
            </div>
            <div class="card-footer">Python, Tensorflow, REST API</div>
          </div>
        </div>

        <div class="col-xl-4 col-md-6 mt-3">
          <div class="card">
            <h3 class="card-header">
              <a href="https://github.com/Matii96/tf-image-classification" target="_blank">Image classificator</a>
            </h3>
            <div class="card-body">Simple graphics classificator based on 2d convolutional network.</div>
            <div class="card-footer">Python, Tensorflow, REST API</div>
          </div>
        </div>

        <div class="col-xl-4 col-md-6 mt-3">
          <div class="card">
            <h3 class="card-header">Object recognition</h3>
            <div class="card-body">
              My master thesis. A far-reaching development of the idea from image classificator. Graphical application
              recogning objects in image in real-time with giving information anout it.Inspired by Marvel's Iron Man's
              helmet.
            </div>
            <div class="card-footer">Python, Tensorflow, Nest.js, Vue.js 2</div>
          </div>
        </div>

        <div class="col-xl-4 col-md-6 mt-3">
          <div class="card">
            <h3 class="card-header">
              <a href="https://github.com/Matii96/students-notes" target="_blank">Students notes</a>
            </h3>
            <div class="card-body">
              Standard crud application, with real-time features, which served me as example for my
              <a
                href="https://medium.com/@matii96/full-stack-design-pattern-for-real-time-apps-in-node-js-and-vue-2-part-1-6d871ec7df79"
                target="_blank"
              >
                article</a
              >.
            </div>
            <div class="card-footer">Node.js, Vue.js 2</div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { Vue } from 'vue-class-component';

export default class projects extends Vue {}
</script>

<style scoped>
#projects {
  background: #f3f2f2;
}
.card-header {
  text-align: center;
}
.card-header,
.card-footer {
  background-color: #fff;
}
</style>
