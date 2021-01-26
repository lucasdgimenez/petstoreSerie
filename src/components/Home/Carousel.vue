<template>
  <div id="carousel">
    <div class="container">
        <a href="">
          ❮
        </a>
        <a href="">
          ❯
        </a>
    </div>
  
  </div>
</template>

<script>
export default {
  name: 'Carousel'
}
</script>

<style scoped>
#carousel {
 
  background-image: url('../../assets/dog.jpg');
  background-position: center;
  background-size: cover;
  padding: 130px;
}

#carousel div {
   display: flex;
  justify-content: space-between;
}

#carousel a {
  color: #fff;
  font-size: 46px;
}
#carousel a:hover {
  background: rgba(0, 0, 0, 0.4);
}


</style>