<!-- App.vue -->

<template>
  <div id="app">
    <ShoppingList :items="shoppingItems" />
  </div>
</template>

<script>
import ShoppingList from "./ShoppingList.vue";

export default {
  components: {
    ShoppingList
  },
  data() {
    return {
      shoppingItems: ["Manzanas", "Leche", "Sabritas", "Coca-Cola", "Jugo"]
    };
  }
};
</script>

<style>
#app {
  text-align: center;
  margin-top: 60px;
}

/* Estilos opcionales para la aplicación principal */
h2 {
  color: #333;
}
</style>
