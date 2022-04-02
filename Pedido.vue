<template>
  <div class= "pedido">
     <h1>Formulario del Pedido</h1>
        <h2>Datos de Contacto</h2>
          <label for="Input1">Nombre del cliente</label>
          <input type="text" id="Input1" name="Input1">
          <label for="correo1">Correo</label>
          <input type="email" id="correo1" name="correo1">
          <label for="tel1">Teléfono de Contacto</label>
          <input type="tel" id="tel1" name="tel1" maxlength="10">
        <h2>Datos del Pastel</h2>
          <label for="sabor1">Sabor del pastel</label>
          <input type="text" id="sabor1" name="sabor1">
          <label for="relleno1">Relleno</label>
          <input type="text" id="relleno1" name="relleno1">
          <label for="comb1">Combinaciones de sabor/relleno</label>
          <input type="text" id="comb1" name="comb1">
          <label for="tpan1">Tipo de pan del pastel</label>
          <input type="text" id="tpan1" name="tpan1">
          <label for="pisos1">Pisos</label>
          <input type="number" id="pisos1" name="pisos1">
          <label for="peso1">Peso del pastel</label>
          <input type="number" id="peso1" name="peso1">
          <label for="personas1">Cantidad de personas </label>
          <input type="number" id="pesonas1" name="personas1">
          <label for="cantidad1">Cantidad de pasteles</label>
          <input type="number" id="cantidad1" name="cantidad1">
          <label for="url1">URL de la imagen de la decoración</label>
          <input type="url" id="url1" name="url1">
        <h2>Datos de la entrega</h2>
          <label for="entrega1">Tipo de entrega</label>
          <input type="text" id="entrega1" name="entrega1">
          <label for="domic1">Domicilio en caso de entrega a domicilio</label>
          <input type="text" id="domic1" name="domic1">
          <label for="fecha1">Fecha de entrega</label>
          <input type="text" id="fecha1" name="fecha1">
          <label for="fpago1">Forma de pago</label>
          <input type="text" id="fpago1" name="fpago1">
  </div>
</template>

<script>
export default {
  name: 'Pedido', 
}
</script>

<style>
.pedido{
  width: 500px;
  height: 600px;
  background-color: #6edaf5;
  position: right;
  border-radius: 7%; 
  text-align: center;
  color: black;
}

</style>