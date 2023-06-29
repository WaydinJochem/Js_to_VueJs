<template>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav> -->
  <NavBarComp/>
  <router-view/>
  <FooterComp/>
</template>
<script>
import NavBarComp from './components/NavBar.vue'
import FooterComp from './components/Footer.vue'

export default {
  components: {
    NavBarComp, FooterComp
  }
}
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Bruno+Ace&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}


body {
  background: linear-gradient(to right, #03001e, #7303c0, #24243e);
  animation: spinning 15s ease infinite;
  background-size: 200% 200%;
  background-attachment: fixed;
  font-family: "Bruno Ace", cursive;
}

@keyframes spinning {
  0% {
    background-position: 0% 0%;
  }

  50% {
    background-position: 100% 150%;
  }

  100% {
    background-position: 0% 0%;
  }
}

h1 {
    text-align: center;
    font-size: xxx-large;
    text-shadow: 10px 10px #333;
}
button {
    padding: 1%;
    box-shadow: 1px 1px #ddd;
    display: block;
    margin-left: auto;
    margin-right: auto;
    margin-top: 2%;
    text-transform: uppercase;
  }
</style>