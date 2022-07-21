<template>
  <body>
    <div class="container">
      <Navbar />
      <!-- head -->
      <section class="head">
        <div class="gradient">
          <img class="gradient" src="~/assets/gradient.png" />
          <img class="apart1" src="~/assets/apart.png" />
        </div>
        <section class="h1">
          <section class="title">
            <p>Find Your</p>
            <p>Dream Home</p>
          </section>
          <section class="sub">
            <p>
              This is where you can find a dream home of your choice without
              stress
            </p>
          </section>
          <section class="search">
            <p>Search the price you are looking for here</p>
          </section>
        </section>
      </section>
      <!-- search -->
    </div>
  </body>
</template>

<script>
// import Navbar from '../components/Navbar/index.vue';
import Navbar from "@/components/Navbar";
import Footer from "@/components/Footer";
export default {
  name: "IndexPage",
  components: { Navbar, Footer },
};
</script>

<style scoped>
@import "~/static/css/home.css";
@import url("https://fonts.googleapis.com/css?family=Montserrat");
@import url("http://fonts.googleapis.com/css?family=Josefin+Sans&subset=latin,latin-ext");
/* @import url("https://cdn.jsdelivr.net/npm/bootstrap@4.1.3/dist/css/bootstrap.min.css"); */
</style>
