<template>
  <div class="cont">
  <div class=" space">
 
    <Inventario/>
    <Pedidos/>
  </div>
    <Footer/>
  </div>

</template>

<script>
import Pedidos from "../components/Pedidos.vue";
import Inventario from "../components/Inventario.vue";
import Footer from "../components/Footer.vue";

export default {
  name: 'Pastelero',
  components:{
    Inventario,
    Pedidos,
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