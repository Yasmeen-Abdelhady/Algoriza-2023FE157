<template>
  <Navbar />
  <Header />
  <div class="container">
    <div class="covid">
      Check the latest COVID-19 restrictions before you travel. <a href="#">Learn more</a>
    </div>
    <DreamVacation />
    <Inspiration />
    <popularHotels />
    <AppSec />
    <DiscoverPlaces /> 
  </div>
  <Footer />
</template>

<script>
import Navbar from "../components/layout/NavbarSec.vue";
import Header from "../components/home/Header.vue";
import DreamVacation from "../components/home/DreamVacation.vue";
import Inspiration from "../components/home/Inspiration.vue";
import popularHotels from "../components/home/popularHotels.vue";
import AppSec from "../components/home/AppSec.vue";
import DiscoverPlaces from "../components/home/DiscoverPlaces.vue";
import Footer from "../components/layout/Footer.vue";

export default {
    name: "homeView",
    components:{Navbar , Header , DreamVacation , Inspiration , popularHotels , AppSec , DiscoverPlaces , Footer}
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
    text-decoration: none;
  }
}
</style>