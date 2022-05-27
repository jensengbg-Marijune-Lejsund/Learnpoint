<template>
  <NavBar></NavBar>
  <Home></Home>
  <Footer></Footer>
</template>

<script>
import Home from "./views/Home.vue"
import NavBar from "./components/NavBar.vue"
import Footer from "./components/Footer.vue"

export default {
  components: { NavBar, Footer, Home },
}
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
