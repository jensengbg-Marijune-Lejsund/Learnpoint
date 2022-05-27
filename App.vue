<template>
  <div id="app"></div>
</template>

import Vue from 'vue'

import BlogPage from '../views/BlogPage.vue'
import BlogPost from '../views/BlogPost.vue'
import Contact from '../views/Contact.vue'
import Home from '../views/Home.vue'
import Pricing from '../views/Pricing.vue'
import Team from '../views/Team.vue'

<script>
export default {
  name: 'App',
};
</script>



<style>
* {
  box-sizing: border-box;
}
html,
body {
  width: 100vw;
  height: 100vh;
  margin: 0;
  padding: 0;
}
body {
  display: flex;
  justify-content: center;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 375px;
}
@media screen and (max-width: 375px) {
  #app {
    width: 100vw;
  }
}
</style>
