<template>
  <section class="about">
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-4">
          <img src="/assets/me.jpg" alt="Me" class="img-responsive me" />
        </div>
        <div class="col-md-5 about-description">
          <div class="heading">
            <h2 class="title">About me</h2>
          </div>
          <h3>Mateusz Fonfara</h3>
          <h4>Full stack developer</h4>

          <p>
            Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, commodo vitae,
            ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis
            tempus lacus enim ac duiQuisque sit amet fermentum elit eget tincidunt
          </p>
          <p>
            Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum
            tortor quam, feugiat vitae, ultricies eget, tempor sit Aenean ultricies mi vitae placerat eleifend leo.
          </p>
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
.about {
  background: #f3f2f2;
  color: #404042;
  /* width: 98.5vw; */
}
.heading {
  padding-top: 78px;
  padding-bottom: 26px;
}
.me {
  width: 100%;
  object-fit: cover;
}
.col-md-4 {
  padding: 0;
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
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 50%;
  }
}
</style>
