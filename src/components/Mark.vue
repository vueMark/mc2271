<template>
<div>
  <h1>{{product}}</h1>
  <vue-simple-spinner message="Loading..."></vue-simple-spinner>
</div>
</template>

<script>
export default {
  data: () => {
  return {
    product:"Kettlebells",
    description:"Cannon ball with a handle"
  }
}
}
</script>

<style>

</style>