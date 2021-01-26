<template>
    <nav id="opcoes">
      <div class="container">
        <a href="" class="opcoes_link">
          <img src="../../assets/racao.jpg" alt="Racao">
          <h2>Ração</h2>
        </a>
        
        <a href="" class="opcoes_link">
          <img src="../../assets/toydog.jpg" alt="Brinquedos">
          <h2>Brinquedos</h2>
        </a>
        
        <a href="" class="opcoes_link">
          <img src="../../assets/boxtransportedog.jpg" alt="Acessorios">
          <h2>Acessorios</h2>
        </a>
      </div>     
    </nav>
</template>

<script>
export default {

}
</script>

<style scoped>
#opcoes {
  background: #dd9f0f;
}
#opcoes div {
  display: flex;
  justify-content: space-between;
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

@media only screen and (max-width: 1024px) {
  #opcoes div {
    flex-direction: column;
    align-items: center;
  }
}

</style>