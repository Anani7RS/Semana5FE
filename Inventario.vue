<template>
  <div class = "inventario">
    <h1>Inventario</h1>
        <div>
            <h2>Sabores</h2>
            <table>
                <tr>
                    <th>Sabores</th>
                    <th>Cantidad</th>
                <tr>
                </tr>
                    <td>Chocolate</td>
                    <td>1 cubeta</td>
                </tr>
            </table>

            <h2>Decoraciones</h2>
            <table>
                <tr>
                    <th>Fondan</th>
                    <th>Cantidad</th>
                </tr>
                    <td>Azul</td>
                    <td>10 kg</td>
                
            </table>
    
            <h2>Ingredientes</h2>
            <table>
                <tr>
                    <th>Ingrediente</th>
                    <th>Cantidad</th>
                <tr>
                </tr>
                    <td>Huevo</td>
                    <td>1 caja</td>
                </tr>
            </table>
        </div>
  </div>
</template>

<script>
export default {
  name: 'Inventario', 
}
</script>

<style>
  .inventario{
    width: 200px;
    height: 420px;
    background-color: rgb(0, 170, 250);
    position: center;
    border-radius: 7%; 
    text-align: center;
    color: white;
  }
</style>