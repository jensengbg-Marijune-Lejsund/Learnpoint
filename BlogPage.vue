<template>
  <div class="blog">
    <div class="nav">
      <NavBar></NavBar>
    </div>
    <div class="title">Blog</div>
    <div class="blog__wrapper">
      <div class="blog__card">
        <img class="blogImage" v-bind:src="code" />
        <div class="bloginfo">
          <p>May 1, 2022</p>
          <h1>Coding is the Future</h1>
          <p class="post">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis
            inventore aperiam nesciunt nisi ullam dicta, placeat vero
            quibusdam incidunt sunt ipsa numquam officia error voluptate
            alias. Veniam laborum sequi omnis?
          </p>
          <a href="blogpost.html">
            <button class="blog__button">Read More</button>
          </a>
        </div>
      </div>
      <div class="blog__card">
        <img class="blogImage" v-bind:src="meeting" />
        <div class="bloginfo">
          <p>April 20, 2022</p>
          <h1>Meeting online now?</h1>
          <p class="post">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis
            inventore aperiam nesciunt nisi ullam dicta, placeat vero
            quibusdam incidunt sunt ipsa numquam officia error voluptate
            alias. Veniam laborum sequi omnis?
          </p>
          <a href="blogpost2.html">
            <button class="blog__button">Read More</button>
          </a>
        </div>
      </div>
      <div class="blog__card">
        <img class="blogImage" v-bind:src="social" />
        <div class="bloginfo">
          <p>April 03, 2022</p>
          <h1>Social Media Today</h1>
          <p class="post">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis
            inventore aperiam nesciunt nisi ullam dicta, placeat vero
            quibusdam incidunt sunt ipsa numquam officia error voluptate
            alias. Veniam laborum sequi omnis?
          </p>
          <a href="blogpost3.html">
            <button class="blog__button">Read More</button>
          </a>
        </div>
      </div>
    </div>
    <div class="more">
      <button>More Blog Posts</button>
    </div>
    <div class="footer">
      <Footer></Footer>
    </div>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import Footer from './components/Footer.vue';
import code from '../assets/code.avif';
import meeting from '../assets/meeting.avif';
import grading from '../assets/social.avif';

export default {
  data: function() {
    return {
      logoImage: logoImage,
      code: code,
      meeting: meeting,
      grading: grading,
    };
  },
  components: {
    NavBar,
    Footer,
  },
};
</script>

<style>
</style>