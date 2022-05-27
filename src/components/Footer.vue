<template>
  <footer>
    <div class="footer__wrapper">
      <div class="footer__card">
        <h2>Learnpoint</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea culpa
          itaque reiciendis, ratione a temporibus odio ipsum cupiditate
          perferendis, explicabo neque, veniam optio tempora aspernatur
          obcaecati recusandae quas ipsa tempore.
        </p>
      </div>
      <div class="footer__card">
        <h2>Contacts</h2>
        <p>012 3456 789</p>
        <p>Box 7</p>
        <p>Stockholm</p>
        <p>learnpoint@lp.se</p>
      </div>
      <div class="footer__card">
        <h2>Links</h2>
        <a class="foot__links" href="home.html">Home</a>
        <a class="foot__links" href="team.html">Our Team</a>
        <a class="foot__links" href="contact.html">Contact</a>
        <a class="foot__links" href="pricing.html">Pricing</a>
        <a class="foot__links" href="index.html">Blog</a>
      </div>
      <div class="footer__card">
        <h2>Connect with Us</h2>
        <img class="foot__connect" src="../../assets/connect.png" alt="" />
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer__wrapper {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-template-rows: 1fr;
  background-color: #0975ff;
  color: white;
  padding: 8px;
}

.footer__card h2 {
  font-family: "Nunito", sans-serif;
  font-weight: 450;
  font-size: 30px;
}

.footer__card {
  margin: 10px;
  display: flex;
  flex-direction: column;
}

.footer__card p {
  font-size: 15px;
  display: flex;
}

.foot__links {
  text-decoration: none;
  font-family: "Raleway", sans-serif;
  color: white;
  cursor: pointer;
  margin-left: 10px;
  padding-top: 10px;
  padding-bottom: 10px;
}

.foot__connect {
  margin-left: -20px;
}
</style>
