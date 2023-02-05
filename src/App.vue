<template>
  <div id="app">
    <productlistone> </productlistone>
    <productlisttwo> </productlisttwo>
   
  </div>
</template>

<script>
import productlistone from "./components/productlistone.vue";
import productlisttwo from "./components/productlisttwo.vue";

export default {
  name:'app',
components:{
  'productlistone': productlistone,
  'productlisttwo': productlisttwo
},

  data() {
    return {
      products: [
        {name: 'apples', price: 35},
        {name: 'bananas', price: 50},
        {name: 'cherries', price:100},
        {name: 'oranges', price:120}
      ]

      
    }
  }
}
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
