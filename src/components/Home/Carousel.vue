<template>
  <div id="carousel">
    <a href="">Anterior</a>
    <a href="">Proximo</a>
  </div>
</template>

<script>
export default {
  name: 'Carousel'
}
</script>

<style scoped>
#carousel {
  display: flex;
  justify-content: space-between;
  background-image: url('../../assets/dog.jpg');
  padding: 130px;
}

</style>