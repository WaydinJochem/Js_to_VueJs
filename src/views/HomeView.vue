<template>
  <!-- <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div> -->
  <main>
    <section id="first-view">
      <h1 id="Store">GuNs GaRloRe</h1>
      <div id="intro">
        <p>Your One Stop Store for Guns and More</p>
        <br />
        <p>Shop no further than Guns Garlore</p>
      </div>
    </section>
    <h2 id="promo">Popular Products</h2>
    <section id="added"></section>
  </main>
</template>

<script>
// @ is an alias to /src


export default {

}
</script>
<style>
#first-view {
  background-image: url('https://i.postimg.cc/rpdqdL5C/istockphoto-1205603080-612x612.jpg');
  background-repeat: no-repeat;
  background-size: 100% 100%;
  padding: 2%;
  color: aliceblue;
}

h1 {
  text-align: center;
  font-size: xxx-large;
  text-shadow: 10px 10px #333;
}

#intro {
  display: flex;
  flex-direction: column;
  align-items: end;
  text-align: center;
  margin: 5%;
}
</style>