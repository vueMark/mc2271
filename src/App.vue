<template>
  <div id="app">
    <Product :premium="premium"/>
  </div>
</template>

<script>
import Product from './components/Product.vue'

export default {
  name: 'App',
  components: {
    Product
  },
  data(){
    return {
      premium: false
    }
  }
}
</script>

<style>

</style>
