<template>
  <section id="destaques" class="container">
    <h1 class="title_home">Destaques</h1>
    <Products/>
  </section>
</template>

<script>
import Products from "../Products"

export default {
  name: 'Destaques',
  components: {
    Products
  }
}
</script>

<style scoped>

</style>