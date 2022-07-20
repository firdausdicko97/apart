<template>
  <header class="header">
    <section class="navbar">
      <div class="navicon">
        <img src="~/assets/navicon.png" />
      </div>

      <section class="nav">
        <a href="">Home</a>
        <a href="">Residence</a>
        <a href="">About Us</a>
        <a href="">Agent</a>
        <a href="">About you</a>
        <a href="" class="button">Login</a>
      </section>
    </section>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>

<style scoped>
@import "~/static/css/navbar.css";
@import url("https://fonts.googleapis.com/css2?family=Gemunu+Libre:wght@200&display=swap");
</style>
