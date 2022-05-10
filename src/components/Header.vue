<template >
  <div v-bind:class="'hero-section'">
    <div v-bind:class="'nav-bar'">
      <div class="logo">
            <h1> <i class="fa-solid fa-mug-saucer"></i> VUE-FOOD</h1>
        </div>
        <div class="navs-2">
      <div class="nav-links">
            <ul>
            <li>
                <a href="#">Home</a>
            </li>
            <li>
                <a href="#">Service</a>
            </li>
            <li>
                <a href="#">Portfolio</a>
            </li>
            <li>
                <a href="#">Pricing</a>
            </li>
            <li>
                <a href="#">Team</a>
            </li>
            <li>
                <a href="#">Contact</a>
            </li>
            </ul>
      </div>
      <div class="nav-icon">
         <h2> <i class="fa-solid fa-bars"></i></h2>
        </div>
        </div>
    </div>
    <div v-bind:class="'hero-content'">
        <div class="hero-text">
    <h1>Minimal  Food Website <br> Vue Template By Codex UI.</h1>
    <br>
    <p>We are a digital agency that helps brands to achieve their business outcomes. We see technology as a
                    tool to create amazing things.</p>
                    <br>
                    <div class="hero-button">
    <button  v-bind:class="'btn'" v-on="btn">ORDER NOW</button>
    <h4> <i class="fa-solid fa-play"></i> &nbsp; Watch Intro</h4>
    </div>
        </div>
        <div class="hero-image">
            <img src="https://nextfood.vercel.app/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fbanner2.8cde3dea.jpg&w=1920&q=75" alt="" style="border-radius: .5em;">
        </div>
    </div>

  </div>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style scoped>
@import "../assets/Header.css";

</style>