<template>
  <h1 class="alert alert-primary" style="text-align: center;">FoodRest Oscar Alejandro Meza Avendaño 10° A</h1>
  <hr />

  <div style="display: grid; grid-template-columns: repeat(3,1fr); gap: 20px;">
    <card url="https://cdn.pixabay.com/photo/2014/10/19/20/59/hamburger-494706_960_720.jpg" nombre="Hamburguesa" descripcion="Hamburguesa de la casa con doble queso" precio="$95"/>
    <card url="https://cdn.pixabay.com/photo/2016/04/04/17/22/meal-1307604_960_720.jpg" nombre="Ensalada" descripcion="Ensalada Especial" precio="$150"/>
    <card url="https://cdn.pixabay.com/photo/2014/11/05/15/57/salmon-518032_960_720.jpg" nombre="Filete de pescado" descripcion="Filete de pescado a la plancha" precio="$115"/>
    <card url="https://cdn.pixabay.com/photo/2017/03/23/19/57/asparagus-2169305_960_720.jpg" nombre="Filete de ternera" descripcion="Filete de ternera con espárragos" precio="$105"/>
    <card url="https://cdn.pixabay.com/photo/2017/05/07/08/56/pancakes-2291908_960_720.jpg" nombre="Hotcakes" descripcion="Hotcakes Torre" precio="$75"/>
    <card url="https://cdn.pixabay.com/photo/2015/04/08/13/13/food-712665_960_720.jpg" nombre="Salmón" descripcion="Salmón Teriyaki" precio="$145"/>

  </div>


  <hr />
  <footer style="background-color: black; color: snow; height: 180px; text-align: center; display: grid; grid-template-columns: repeat(3,1fr);">
    <p>Lorem ipsum</p>
    <p>Lorem ipsum</p>
    <p>Lorem ipsum</p>
    <p>Lorem ipsum</p>
    <p>Lorem ipsum</p>
    <p>Lorem ipsum</p>
    <p>Lorem ipsum</p>
    <p>Lorem ipsum</p>
    <p>Lorem ipsum</p>
  </footer>

</template>

<script>
  import Card from "./components/Card.vue";

  export default {
      components: { Card },
  };
</script>