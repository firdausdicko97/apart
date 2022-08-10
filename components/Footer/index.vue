<template>
  <section class="footer">
    <div class="footer-main">
      <img src="~/assets/footericon.png" alt="" />
      <p>
        Our goal is at the <br />
        heart of all that we do.
      </p>
      <div class="footer-social">
        <img class="footer-social-img" src="~/assets/facebook.png" alt="" />
        <img class="footer-social-img" src="~/assets/twitter.png" alt="" />
        <img class="footer-social-img" src="~/assets/linkedin.png" alt="" />
      </div>
    </div>
    <div class="footer-page"></div>
    <div class="footer-support"></div>
    <div class="footer-about-us"></div>
  </section>
</template>

<script>
export default {
  name: "AppFooter",
};
</script>

<style scoped>
@import "~/static/css/footer.css";
@import url("https://fonts.googleapis.com/css2?family=Gemunu+Libre:wght@200&display=swap");
</style>
