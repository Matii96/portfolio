<template>
  <section id="education">
    <div class="container pt-5 pb-5">
      <center><h2 class="title">EDUCATION</h2></center>
      <div class="main-timeline">
        <!-- start education section-->
        <div class="timeline mt-4">
          <div class="icon"></div>
          <div class="date-content" style="margin-top: 28px">
            <div class="date-outer">
              <span class="date">
                <span class="month">2 Years</span>
                <span class="year">2018</span>
              </span>
            </div>
          </div>
          <div class="timeline-content">
            <h5 class="timeline-title">
              <a href="http://wmii.uwm.edu.pl" target="_blank">University of Warmia and Mazury in Olsztyn</a>
              <h6 class="timeline-subtitle">Faculty of Mathematics and Computer Science</h6>
            </h5>
            <p class="description">Master's degree in software engineering.</p>
          </div>
        </div>
        <!-- end education section-->

        <!-- start education section-->
        <div class="timeline mt-4">
          <div class="icon"></div>
          <div class="date-content" style="margin-top: 28px">
            <div class="date-outer">
              <span class="date">
                <span class="month">3,5 Years</span>
                <span class="year">2015</span>
              </span>
            </div>
          </div>
          <div class="timeline-content">
            <h5 class="timeline-title">
              <a href="http://wmii.uwm.edu.pl" target="_blank">University of Warmia and Mazury in Olsztyn</a>
              <h6 class="timeline-subtitle">Faculty of Mathematics and Computer Science</h6>
            </h5>
            <p class="description">Bachelor of Engineering.</p>
          </div>
        </div>
        <!-- end education section-->
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { Vue } from 'vue-class-component';

export default class Education extends Vue {}
</script>
