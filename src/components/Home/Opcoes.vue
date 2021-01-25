<template>
    <nav id="opcoes">
      <a href="" class="opcoes_link">
        <img src="../../assets/racao.jpg" alt="">
        <h2>Ração</h2>
      </a>
      
      <a href="" class="opcoes_link">
        <img src="../../assets/toydog.jpg" alt="">
        <h2>Brinquedos</h2>
      </a>
      
      <a href="" class="opcoes_link">
        <img src="../../assets/racao.jpg" alt="">
        <h2>Acessorios</h2>
      </a>
    </nav>
</template>

<script>
export default {

}
</script>

<style scoped>
#opcoes {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  padding-top: 10px;
}

#opcoes img {
  height: 100px;
  width: 300px;
  filter: brightness(.5);
}

#opcoes h2 {
  position: relative;
  color: #fff;
  text-transform: uppercase;
  text-align: center;
    top: -70px;
  margin-bottom: -20px;
}

</style>