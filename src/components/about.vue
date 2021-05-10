<template>
  <section id="about">
    <div class="container-fluid">
      <div class="row">
        <div class="col-sm-4">
          <img src="/assets/me.jpg" alt="Me" class="img-responsive me" />
        </div>
        <div class="col-sm-5 about-description">
          <div class="heading">
            <h2 class="title">About me</h2>
          </div>
          <h3>Mateusz Fonfara</h3>
          <h4>Full Stack Developer</h4>

          <p>
            Hi, I’m Matthew. Nice to meet you 😉
            <br />My passion is creating tools for other people to make their life easier, save time having fun at the
            same time. I have experience with each stage of creating applications, from its concept, by the design and
            architecture planning to final execution and deployment. I run a blog on medium.com where I share my
            thoughts on the IT world and contribute to open source.
          </p>
          <!-- <div class="container contact mt-4 mb-4">
            <div class="row align-items-center">
              <div class="col-xl-2 col-4">
                <a href="https://github.com/Matii96" target="_blank" class="contact-link">
                  <i class="fa fa-github fa-5x round" />
                </a>
              </div>
              <div class="col-xl-2 col-4">
                <a href="https://medium.com/@matii96" target="_blank" class="contact-link">
                  <i class="fa fa fa-medium fa-5x round" />
                </a>
              </div>
              <div class="col-xl-2 col-4">
                <a href="mailto:mateusz.fonfara96@gmail.com" class="contact-link">
                  <i class="fa fa-envelope fa-5x round" />
                </a>
              </div>
            </div>
          </div> -->
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { Vue } from 'vue-class-component';

export default class About extends Vue {}
</script>

<style scoped>
#about {
  background: #f3f2f2;
  color: #404042;
}
.heading {
  padding-top: 70px;
  padding-bottom: 26px;
}
.me {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.col-sm-4 {
  padding: 0;
}
.col-sm-5 {
  margin-left: 20px;
}

.contact {
  font-size: 0.35rem;
  display: inline-block;
  left: 0;
}
.contact-link {
  color: #000;
  margin-left: 10px;
  margin-right: 10px;
}
.contact-link:hover {
  color: rgba(0, 0, 0, 0.6);
}
.fa.round {
  display: inline-block;
  border-radius: 60px;
  box-shadow: 0px 0px 2px #888;
  padding: 0.5em 0.6em;
}

@media only screen and (max-width: 1060px) {
  .heading {
    padding-top: 10px;
  }
}

@media only screen and (max-width: 760px) {
  .me {
    height: 260px;
  }
  .about-description {
    margin-left: 30px;
    margin-right: 30px;
  }
  .heading {
    padding-top: 70px;
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 70%;
  }
}
</style>
