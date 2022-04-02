<template>
  <div class="cont">
  <div class=" space">

    <Sabores/>
    <Decoraciones/>
    <Pedido/>
  </div>
    <Footer/>
  </div>
</template>

<script>
import Pedido from "../components/Pedido.vue";
import Sabores from "../components/Sabores.vue";
import Decoraciones from "../components/Decoraciones.vue";
import Footer from "../components/Footer.vue";

export default {
  name: 'Pedidos',
  components:{
    Sabores,
    Decoraciones,
    Pedido,
    Footer
  }
}
</script>

<style>
  .space{
  justify-content:flex-start;
  }
  
  .cont > div{
  display: flex;
  }
</style>