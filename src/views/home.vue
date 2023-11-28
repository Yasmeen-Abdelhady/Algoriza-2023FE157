<template>
  <Navbar />
  <Header />
  <div class="container">
    <div class="covid">
      Check the latest COVID-19 restrictions before you travel. <a href="#">Learn more</a>
    </div>
  </div>
</template>

<script>
import Navbar from "../components/layout/NavbarSec.vue";
import Header from "../components/home/Header.vue";

export default {
    name: "homeView",
    components:{Navbar , Header}
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/_variables.scss";

.covid{
  background-color: $Warning;
  padding: 15px 30px;
  border-radius: 8px;
  margin-top: 50px;
  margin-bottom: 30px;
  a{
    color: $PrimaryColor;
  }
}
</style>