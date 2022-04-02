<template>
  <div class="home">
    <h1>"PASTELERÍA ANELIS"</h1>
    <img alt="Pasteleria" src= "../assets/Pastel.jpg">

    <Inicio/>
    <Footer/>
  </div>
</template>

<script>
import Inicio from "../components/Inicio.vue";
import Pastelero from "../components/Pastelero.vue";
import Footer from "../components/Footer.vue";

export default {
  name: 'HomeView', 
  components:{
    Inicio,
    Footer
  }
}
</script>