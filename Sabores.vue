<template>
  <div class="sabores">
    <h1>Sabores y Precios</h1>
      <table>
        <tr>
          <th>Sabores</th>
          <th>Rellenos</th>
          <th>Tipo de Pan</th>
          <th>Tamaño</th>
          <th>Pisos del Pastel</th>
          <th>Total de Personas</th>
                    
        <tr>
        </tr>
          <td>vanilla $74 </td>
          <td> Frutas $60 </td>
          <td> 3 leches $64 </td>
          <td> 1kg $74 </td>
          <td> 1 piso $60 </td>
          <td> 10 personas $250 </td>
        </tr>
      </table>
  </div>
</template>

<script>
export default {
  name: 'Sabores', 
}
</script>

<style>
.sabores{
  width: 500px;
  height: 200px;
  background-color: rgb(0, 170, 250);
  position: center;
  border-radius: 7%; 
  text-align: center;
  color: black;
}
</style>