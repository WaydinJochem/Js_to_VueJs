<template>
    <footer>
        <div id="conditions">
            <div>
                <h3>Contact Us At:</h3>
                <p>619 Masterio Estate</p>
                <p>Populas 51</p>
                <p>Planet 999</p>
                <p>Galaxy #4</p>
            </div>
            <div>Not for Sale to humans under 300years old</div>
            <div>Terms And Conditions</div>
        </div>
        <div class="sections">
            <p id="copy">&copy;NeglectedNPC 2023</p>
        </div>
        <div class="links">
            <router-link to="https://twitter.com/"><img src="../assets/icons8-twitter-circled-2.gif" alt=""
                    class="icons" /></router-link>
            <router-link to="https://za.linkedin.com/?original_referer=https%3A%2F%2Fwww.google.com%2F"><img
                    src="../assets/icons8-linkedin-circled-1.gif" alt="" class="icons" /></router-link>
            <router-link to="https://www.instagram.com/"><img src="../assets/icons8-instagram-1.gif" alt=""
                    class="icons" /></router-link>
            <router-link to="https://www.instagram.com/"><img src="../assets/icons8-github-1.gif" alt=""
                    class="icons" /></router-link>
        </div>
    </footer>
</template>
<script>
export default {

}
</script>
<style scoped>
.links {
text-align: center;
}

footer {
    background-color: rgb(59, 5, 59);
    padding: 2%;
  }
  
  .sections {
    text-align: center;
  }
  #copy {
    font-size: large;
  }
  .icons {
    width: 2%;
    border-radius: 50%;
    /* do media query*/
  }
  #conditions {
    display: grid;
    grid-template-columns: auto auto auto;
    align-items: center;
    margin-left: 5%;
  }
</style>