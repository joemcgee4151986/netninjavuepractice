<template>
  <div id="app">
   <product-list-one> </product-list-one>
   <product-list-two> </product-list-two>
   
  </div>
</template>

<script>


export default {
  name: 'App',
  data() {
    return {
      products: [
        {name: 'apples', price: 35},
        {name: 'bananas', price: 50},
        {name: 'cherries', price:100}
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
