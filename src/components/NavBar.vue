<template>
  <nav id="first-view">
    <div id="mySidenav" class="sidenav">
      <div id="top">
        <router-link to="/">
          <img
            src="https://i.postimg.cc/xTjh0n2R/Free-Sample-By-Wix.png"
            alt=""
            id="logo"
        /></router-link>
        <!-- <router-link to="/" @click="openNav"> &times;</router-link> -->
      </div>
      <div id="hover">
        <router-link to="/products"> Proudcts</router-link> |
        <router-link to="/about"> About</router-link>    |
        <router-link to="/admin"> Admin</router-link>    |
        <router-link to="/contact"> Contact</router-link>
      </div>
    </div>
  </nav>
</template>

<style scoped>
#hover {
    display: flex;
    font-family: "Bruno Ace", cursive;
    margin-left: 20px;
    letter-spacing: 10px;
    justify-content: center;
}

a {
    color: white;
}

#top {
   text-align: center;
}


</style>