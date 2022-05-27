<template>
  <div class="app">
    <p>{{ count }}</p>
    <div class="nav">
      <NavBar></NavBar>
    </div>
    <div class="home">
      <div class="hero">
        <div class="title">
          <h1>Learnpoint</h1>
        </div>
        <h2>Integrated LMS and SIS</h2>
        <p class="call__us">Need help now? Call us directly at 0123 345 323</p>
        <h2>
          Create programs, write announcements, enroll students, hand out
          assignments, and assess student work. All in one place.
        </h2>
      </div>
      <div class="sections">
        <div class="section">
          <img class="homeCard" v-bind:src="announcements" />
        </div>
        <div class="section">
          <img class="homeCard" v-bind:src="assignments" />
        </div>
        <div class="section">
          <img class="homeCard" v-bind:src="grading" />
        </div>
      </div>

      <div class="demo">
        <h2>Want to know more?</h2>
        <p>
          Would you like a demo, ask a question, or perhaps just talk to us? We'd
          be happy to hear from you.
        </p>
        <p>Write to us at info@learnpoint.se</p>
        <img class="heart" v-bind:src="heart" />
      </div>
    </div>
    <div class="footer">
      <Footer></Footer>
    </div>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import Footer from './components/Footer.vue';
import announcements from '../assets/announcements.png';
import assignments from '../assets/assignments.png';
import grading from '../assets/grading.png';
import heart from '../assets/heart2.png';

export default {
  data: function() {
    return {
      logoImage: logoImage,
      announcements: announcements,
      assignments: assignments,
      grading: grading,
      heart: heart,
    };
  },
  components: {
    NavBar,
    Footer,
  },
};
</script>

<style>
.sections {
  margin: 0 auto;
  text-align: center;
  max-width: 1500px;
}

.section img {
  width: 100%;
}
</style>