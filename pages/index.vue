<template>
  <body>
    <div class="container">
      <Navbar />
      <section class="head">
        <div class="gradient">
          <img class="gradient1" src="~/assets/ellipse1.png" />
          <img class="gradient2" src="~/assets/ellipse2.png" />
          <img class="gradient3" src="~/assets/ellipse2.png" />
        </div>
      </section>
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
</style>
