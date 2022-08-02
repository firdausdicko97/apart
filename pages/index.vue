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
          <!-- Search Start -->
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
      <!-- search end -->
      <!-- Value start -->
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
      <!-- Value end -->
      <!-- Popular start -->
      <section class="popular">
        <p class="popular_text">Popular</p>
        <div class="popular_title">
          <p class="section_title">Our popular residence</p>
          <button class="explore_all">Explore all -></button>
        </div>
        <!--  -->
        <div class="popular_card">
          <div class="popular_card">
            <div class="card">
              <img
                class="card-img-top"
                src="~/assets/popular1.png"
                alt="Card image cap"
              />
              <div class="card-body">
                <h5 class="card-title mb-4">Card title</h5>
                <div class="location mb-3">
                  <img
                    src="~/assets/location.png"
                    alt=""
                    style="width: 15px; height: 20px"
                  />
                  <div class="location-detail ml-3">Jl. kebaikan no. 666</div>
                </div>
                <div class="button-price">
                  <button
                    type="button"
                    class="btn btn-dark"
                    style="margin: 10px; height: 35px; width: 100px"
                  >
                    Dark
                  </button>
                  <p class="price">Rp. 1.000.000.000</p>
                </div>
              </div>
            </div>
          </div>
          <!--  -->
          <div class="popular_card">
            <div class="card">
              <img
                class="card-img-top"
                src="~/assets/popular1.png"
                alt="Card image cap"
              />
              <div class="card-body">
                <h5 class="card-title mb-4">Card title</h5>
                <div class="location mb-3">
                  <img
                    src="~/assets/location.png"
                    alt=""
                    style="width: 15px; height: 20px"
                  />
                  <div class="location-detail ml-3">Jl. kebaikan no. 666</div>
                </div>
                <div class="button-price">
                  <button
                    type="button"
                    class="btn btn-dark"
                    style="margin: 10px; height: 35px; width: 100px"
                  >
                    Dark
                  </button>
                  <p class="price">Rp. 1.000.000.000</p>
                </div>
              </div>
            </div>
          </div>
          <!--  -->
          <div class="card">
            <img
              class="card-img-top"
              src="~/assets/popular1.png"
              alt="Card image cap"
            />
            <div class="card-body">
              <h5 class="card-title mb-4">Card title</h5>
              <div class="location mb-3">
                <img
                  src="~/assets/location.png"
                  alt=""
                  style="width: 15px; height: 20px"
                />
                <div class="location-detail ml-3">Jl. kebaikan no. 666</div>
              </div>
              <div class="button-price">
                <button
                  type="button"
                  class="btn btn-dark"
                  style="margin: 10px; height: 35px; width: 100px"
                >
                  Dark
                </button>
                <p class="price">Rp. 1.000.000.000</p>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- Popular end -->
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
