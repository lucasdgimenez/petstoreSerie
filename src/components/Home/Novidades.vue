<template>
  <section id="novidades" class="container">
    <h1 class="title_home">Novidades</h1>
    <div class="novidadesProdutos">
      <ul>
        <li v-for="item in produtos.slice(0,4)" :key="item.id">
          <a href="">
            <img :src="require(`../../assets/produtos/${item.codimg}.jpg`)" :alt="` ${item.nome}`">
          </a>
          <span v-if="item.new">NOVO</span>
          <h3>{{item.nome}}</h3>
          <p>R$ {{item.preco}}</p>
        </li>
      </ul>
    </div>

    <div class="novidadesCategoria">
      <a href="">
        <img src="../../assets/vitolic.jpg" alt="para Gato">
        <h2>Para Gatos</h2>
      </a>
      <a href="" class="dog">
        <img src="../../assets/karsten.jpg" alt="para Cachorro">
        <h2>Para Cachorros</h2>
      </a>
    </div>
  </section>
</template>

<script>
import produtos from "../../data/produtos.json"

export default {
  name: 'Novidades',
  data() {
    return {
      mouseOn: false,
      produtos: produtos
    }
  },
  created() {
    console.log("Novidade: " + produtos)
  }
}
</script>

<style scoped>
#novidades h1 {
  margin-top: 20px;

}
.novidadesProdutos ul {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

.novidadesProdutos ul li {
  text-align: center;
  margin-top: 5px;
  margin-right: 5px;
  margin-left: 5px;
  margin-bottom: 30px;
}

.novidadesProdutos h3:nth-child(odd) {
  margin-top: -20px;
}

.novidadesProdutos span {
  position: relative;
  color: #fff;
  text-transform: uppercase;
  text-align: center;
  top: -172px;
  right: 80px;
  background: #8257C6;
  padding: 5px;
}

.novidadesProdutos h3 {
  font-weight: 500;
  color: #999
}

.novidadesProdutos p {
  font-weight: 500;
  color: #00002F;
}

.novidadesProdutos ul li a img:hover {
  filter: brightness(.5);
}

.novidadesCategoria a:hover {
    filter: brightness(.5);

}

.novidadesCategoria {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  padding-top: 10px;
}

.novidadesCategoria img, .novidadesProdutos img {
  margin: 0 auto;
}

.novidadesProdutos img {
  width: 240px;
  height: 180px;
}

.novidadesCategoria img {
  width: 480px;
  height: 230px;
}

.novidadesCategoria h2 {
  background: #dd9f0f;
  color: #fff;
  text-align: center;
  text-transform: uppercase;
  padding: 10px;
  position: relative;
  font-weight: 500;
  font-size: 1rem;
  top: -85px;
  width: 190px;
}

@media only screen and (max-width: 1024px) {
  .novidadesCategoria {
    flex-direction: column;
    align-items: center;
  }
}

@media only screen and (max-width: 768px) {
  .novidadesProdutos ul {
    flex-direction: column;
    align-items: center;
  }
}

@media only screen and (max-width: 768px) {
  .novidadesCategoria img {
    width: 300px;
    height: 200px;
  }
  .novidadesCategoria h2 {
    background: #dd9f0f;
    color: #fff;
    padding: 5px;
    font-size: 0.8rem;
    width: 110px;
  }
}

</style>