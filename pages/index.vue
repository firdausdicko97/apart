<template>
  <body>
    <div>
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
          <!-- Search -->
          <section class="search">
            <p>Search the price you are looking for here</p>
            <div class="filter">
              <div class="filter_input">
                <div class="input-group input-group-lg">
                  <input
                    type="text"
                    class="form-control"
                    aria-label="Sizing example input"
                    aria-describedby="inputGroup-sizing-lg"
                  />
                  <div class="input-group-prepend">
                    <span class="input-group-text" id="inputGroup-sizing-lg"
                      ><img src="~/assets/home_icon.png" alt=""
                    /></span>
                  </div>
                </div>
              </div>
              <!--  -->
              <div class="filter_input">
                <div class="input-group input-group-lg">
                  <input
                    type="text"
                    class="form-control"
                    aria-label="Sizing example input"
                    aria-describedby="inputGroup-sizing-lg"
                  />
                  <div class="input-group-prepend">
                    <span class="input-group-text" id="inputGroup-sizing-lg"
                      ><img src="~/assets/location.png" alt=""
                    /></span>
                  </div>
                </div>
              </div>
              <!--  -->
              <div class="filter_input">
                <div class="input-group input-group-lg">
                  <input
                    type="text"
                    class="form-control"
                    aria-label="Sizing example input"
                    aria-describedby="inputGroup-sizing-lg"
                  />
                  <div class="input-group-prepend">
                    <span class="input-group-text" id="inputGroup-sizing-lg"
                      ><img src="~/assets/harga.png" alt=""
                    /></span>
                  </div>
                </div>
              </div>
              <!--  -->
              <button
                type="button"
                class="btn btn-dark"
                style="width: 150px; height: 50px"
              >
                Search Now
              </button>
            </div>
          </section>
        </section>
      </section>
      <!-- search -->
      <!-- Value -->
      <section class="value">
        <!-- value 1 -->
        <div class="value_content">
          <p class="value_title">2100+</p>
          <p class="value_sub">Premium House</p>
        </div>
        <p class="batas">|</p>
        <!-- value 2 -->
        <div class="value_content">
          <p class="value_title">2000+</p>
          <p class="value_sub">Happy Customers</p>
        </div>
        <p class="batas">|</p>
        <!-- value 3 -->
        <div class="value_content">
          <p class="value_title">50+</p>
          <p class="value_sub">Awards</p>
        </div>
      </section>
      <!-- Value -->
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
@import url("https://cdn.jsdelivr.net/npm/bootstrap@4.1.3/dist/css/bootstrap.min.css");
</style>
