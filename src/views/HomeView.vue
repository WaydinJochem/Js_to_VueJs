<template>
  <!-- <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div> -->
  <HomePageComp/>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HomePageComp from "@/components/HomeComp.vue"

export default {
  components: {
   HomePageComp
  }
}
</script>
