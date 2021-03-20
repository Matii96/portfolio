<template>
  <section>
    <div class="container">
      <center><h2 class="title">SKILLS</h2></center>

      <div class="row mt-5">
        <div class="col-md-3 mt-3">
          <div class="row">
            <div class="col-12">
              <div class="card">
                <div class="card-body">
                  <h5 class="card-title text-center mb-4">Frontend</h5>
                  <ul class="list-unstyled text-secondary">
                    <li class="mb-2"><i class="fa fa-check mr-1 text-primary"></i> Javascript / HTML</li>
                    <li class="mb-2"><i class="fa fa-check mr-1 text-primary"></i> CSS / SASS / LESS</li>
                    <li class="mb-2"><i class="fa fa-check mr-1 text-primary"></i> Vue.js</li>
                    <li class="mb-2"><i class="fa fa-check mr-1 text-primary"></i> Angular</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-3 mt-3">
          <div class="row">
            <div class="col-12">
              <div class="card">
                <div class="card-body">
                  <h5 class="card-title text-center mb-4">Backend</h5>
                  <ul class="list-unstyled text-secondary">
                    <li class="mb-2"><i class="fa fa-check mr-1 text-primary"></i> Node.js / Nest.js</li>
                    <li class="mb-2"><i class="fa fa-check mr-1 text-primary"></i> PHP / Symfony</li>
                    <li class="mb-2"><i class="fa fa-check mr-1 text-primary"></i> PostgresSQL / MySQL</li>
                    <li class="mb-2"><i class="fa fa-check mr-1 text-primary"></i> MongoDB</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-3 mt-3">
          <div class="row">
            <div class="col-12">
              <div class="card">
                <div class="card-body">
                  <h5 class="card-title text-center mb-4">Architectures</h5>
                  <ul class="list-unstyled text-secondary">
                    <li class="mb-2"><i class="fa fa-check mr-1 text-primary"></i> Monolithic</li>
                    <li class="mb-2"><i class="fa fa-check mr-1 text-primary"></i> Microservices</li>
                    <li class="mb-2"><i class="fa fa-check mr-1 text-primary"></i> REST</li>
                    <li class="mb-2"><i class="fa fa-check mr-1 text-primary"></i> Stateful (Socket.IO)</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-3 mt-3">
          <div class="row">
            <div class="col-12">
              <div class="card">
                <div class="card-body">
                  <h5 class="card-title text-center mb-4">DevOps & Other</h5>
                  <ul class="list-unstyled text-secondary">
                    <li class="mb-2"><i class="fa fa-check mr-1 text-primary"></i> Git</li>
                    <li class="mb-2"><i class="fa fa-check mr-1 text-primary"></i> Docker / Docker swarm</li>
                    <li class="mb-2"><i class="fa fa-check mr-1 text-primary"></i> Atlassian Bamboo</li>
                    <li class="mb-2"><i class="fa fa-check mr-1 text-primary"></i> Amazon ECR</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { Vue } from 'vue-class-component';

export default class Skills extends Vue {}
</script>

<style scoped>
.card-title {
  font-weight: bold;
}
ul > li {
  margin-left: 10px;
}
</style>
