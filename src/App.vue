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
/* #app {
  font-family: "Bruno Ace", cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
} */
</style>