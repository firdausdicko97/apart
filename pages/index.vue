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
        <p class="title-small">Popular</p>
        <div class="popular_title">
          <p class="section-title mb-3">Our popular residence</p>
          <button class="explore_all">
            Explore all
            <img
              class="ml-1 mr-1"
              src="~/assets/right-arrow.png"
              alt=""
              style="width: 25px"
            />
          </button>
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
                <h5 class="card-title mb-4">Garden House</h5>
                <div class="location mb-3">
                  <img
                    src="~/assets/location.png"
                    alt=""
                    style="width: 15px; height: 20px"
                  />
                  <div class="location-detail ml-3">Jl. kebaikan no. 666</div>
                </div>
                <div class="facility">
                  <div class="facility-item">
                    <img src="~/assets/bed.png" alt="" />
                    <p class="ml-3">4 bed</p>
                  </div>
                  <div class="facility-item">
                    <img
                      src="~/assets/rectangle.png"
                      alt=""
                      style="width: 22px"
                    />
                    <p class="ml-3">10 x 10</p>
                  </div>
                  <div class="facility-item">
                    <img
                      src="~/assets/rectangle.png"
                      alt=""
                      style="width: 22px"
                    />
                    <p class="ml-3">2000m<sup>2</sup></p>
                  </div>
                </div>
                <div class="button-price">
                  <button
                    type="button"
                    class="btn btn-dark"
                    style="margin: 10px; height: 35px; width: 100px"
                  >
                    Buy Now
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
                <h5 class="card-title mb-4">Farm House</h5>
                <div class="location mb-3">
                  <img
                    src="~/assets/location.png"
                    alt=""
                    style="width: 15px; height: 20px"
                  />
                  <div class="location-detail ml-3">Jl. Bandung no. 999</div>
                </div>
                <div class="facility">
                  <div class="facility-item">
                    <img src="~/assets/bed.png" alt="" />
                    <p class="ml-3">4 bed</p>
                  </div>
                  <div class="facility-item">
                    <img
                      src="~/assets/rectangle.png"
                      alt=""
                      style="width: 22px"
                    />
                    <p class="ml-3">10 x 10</p>
                  </div>
                  <div class="facility-item">
                    <img
                      src="~/assets/rectangle.png"
                      alt=""
                      style="width: 22px"
                    />
                    <p class="ml-3">1000m<sup>2</sup></p>
                  </div>
                </div>
                <div class="button-price">
                  <button
                    type="button"
                    class="btn btn-dark"
                    style="margin: 10px; height: 35px; width: 100px"
                  >
                    Buy Now
                  </button>
                  <p class="price">Rp. 10.000.000.000</p>
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
                <h5 class="card-title mb-4">Farm House</h5>
                <div class="location mb-3">
                  <img
                    src="~/assets/location.png"
                    alt=""
                    style="width: 15px; height: 20px"
                  />
                  <div class="location-detail ml-3">Jl. Bandung no. 999</div>
                </div>
                <div class="facility">
                  <div class="facility-item">
                    <img src="~/assets/bed.png" alt="" />
                    <p class="ml-3">4 bed</p>
                  </div>
                  <div class="facility-item">
                    <img
                      src="~/assets/rectangle.png"
                      alt=""
                      style="width: 22px"
                    />
                    <p class="ml-3">10 x 10</p>
                  </div>
                  <div class="facility-item">
                    <img
                      src="~/assets/rectangle.png"
                      alt=""
                      style="width: 22px"
                    />
                    <p class="ml-3">1000m<sup>2</sup></p>
                  </div>
                </div>
                <div class="button-price">
                  <button
                    type="button"
                    class="btn btn-dark"
                    style="margin: 10px; height: 35px; width: 100px"
                  >
                    Buy Now
                  </button>
                  <p class="price">Rp. 10.000.000.000</p>
                </div>
              </div>
            </div>
          </div>
          <!--  -->
          <!--  -->
        </div>
      </section>
      <!-- Popular end -->
      <!-- Benefit start -->
      <section class="benefit">
        <div class="benefit_head mb-3">
          <p class="section_title">Why choose us</p>
          <p class="section-description">
            Our goal is at the heart of all that we do. We make our clients
            happiness our sole priority.
          </p>
        </div>
        <!--  -->
        <div style="margin-bottom: 100px">
          <div class="benefit_card">
            <div class="card">
              <div class="card-body">
                <div class="card-title">
                  <img src="~/assets/insurance.png" alt="" />
                  <p>Insurance</p>
                </div>
                <div class="card-content">
                  <p>
                    This is where you can find a dream home of your choice
                    without stThis is where you can find a dream home of your
                    choice without stressresThis is where you
                  </p>
                </div>
              </div>
            </div>
            <!--  -->
            <div class="card">
              <div class="card-body">
                <div class="card-title">
                  <img src="~/assets/insurance.png" alt="" />
                  <p>Insurance</p>
                </div>
                <div class="card-content">
                  <p>
                    This is where you can find a dream home of your choice
                    without stThis is where you can find a dream home of your
                    choice without stressresThis is where you
                  </p>
                </div>
              </div>
            </div>
            <!--  -->
            <div class="card">
              <div class="card-body">
                <div class="card-title">
                  <img src="~/assets/insurance.png" alt="" />
                  <p>Insurance</p>
                </div>
                <div class="card-content">
                  <p>
                    This is where you can find a dream home of your choice
                    without stThis is where you can find a dream home of your
                    choice without stressresThis is where you
                  </p>
                </div>
              </div>
            </div>
          </div>
          <!--  -->
          <div class="benefit_card">
            <div class="card">
              <div class="card-body">
                <div class="card-title">
                  <img src="~/assets/insurance.png" alt="" />
                  <p>Insurance</p>
                </div>
                <div class="card-content">
                  <p>
                    This is where you can find a dream home of your choice
                    without stThis is where you can find a dream home of your
                    choice without stressresThis is where you
                  </p>
                </div>
              </div>
            </div>
            <!--  -->
            <div class="card">
              <div class="card-body">
                <div class="card-title">
                  <img src="~/assets/insurance.png" alt="" />
                  <p>Insurance</p>
                </div>
                <div class="card-content">
                  <p>
                    This is where you can find a dream home of your choice
                    without stThis is where you can find a dream home of your
                    choice without stressresThis is where you
                  </p>
                </div>
              </div>
            </div>
            <!--  -->
            <div class="card">
              <div class="card-body">
                <div class="card-title">
                  <img src="~/assets/insurance.png" alt="" />
                  <p>Insurance</p>
                </div>
                <div class="card-content">
                  <p>
                    This is where you can find a dream home of your choice
                    without stThis is where you can find a dream home of your
                    choice without stressresThis is where you
                  </p>
                </div>
              </div>
            </div>
            <!--  -->
          </div>
        </div>
      </section>
      <!-- Benefit end -->
      <!-- Team Start -->
      <div class="team-head">
        <p class="title-small">Our team</p>
        <p class="section-title">Meet our team</p>
        <p class="section-description" style="padding-bottom: 0">
          Our goal is at the heart of all that we do. We make our
        </p>
        <p class="section-description">clients happiness our sole priority.</p>
      </div>
      <div class="team-content">
        <div class="chief">
          <img src="~/assets/ceo.png" alt="" class="team-img" />
          <p class="team-name">Adi Purnama</p>
          <p class="team-position">Chief of Executive Officer</p>
        </div>
        <div class="chief">
          <img src="~/assets/cto.png" alt="" class="team-img" />
          <p class="team-name">Rigen</p>
          <p class="team-position">Chief of Technology Officer</p>
        </div>
        <div class="chief">
          <img src="~/assets/ceo.png" alt="" class="team-img" />
          <p class="team-name">Nanank</p>
          <p class="team-position">Chief of Product Officer</p>
        </div>
      </div>
      <!-- Team End -->
      <Footer />
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
