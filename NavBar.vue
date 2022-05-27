<template>
  <nav>
    <div class="navbar">
      <a class="learnpoint__logo" href="home.html"></a>
      <img class="navLogo" v-bind:src="logoImage" />
      <a class="signin" href="signin">Sign In</a>
    </div>
  </nav>
</template>

<script>
import logoImage from '../assets/learnpoint-logo.png';

export default {
  data: function() {
    return {
      logoImage: logoImage,
    };
  },
};
</script>

<style scoped>
.signin {
  font-family: 'Raleway', sans-serif;
  color: black;
  text-decoration: none;
  font-weight: 400;
  font-size: 24px;
  display: flex;
  align-items: flex-end;
}

.navbar {
  padding: 5px;
  display: flex;
  align-items: center;
}

.navLogo {
  display: flex;
  height: 2.5rem;
}
</style>