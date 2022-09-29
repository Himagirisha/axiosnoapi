<template>
  <div id="app">
    <products-main />
    <base-card mobileName="MotoRola g82 6gb ram"
    rating="4" mobilePrice="14000"/>
    <base-card mobileName="onePlus 7 pro 6gb ram"
    rating="4.5" mobilePrice="49000"/>
    
  </div>
</template>

<script>
import BaseCard from './components/BaseCard.vue';
import ProductsMain from "./components/Products-main.vue";
export default {
  name: "App",
  components: { ProductsMain, BaseCard },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
