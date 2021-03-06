<template>
   <div class="novidadesProdutos">
      <ul>
        <li v-for="item in produtos" :key="item.id">
          <a href="">
            <img :src="require(`../assets/produtos/${item.codimg}.jpg`)" :alt="` ${item.nome}`">
          </a>
          <span v-if="item.new">NOVO</span>
          <h3>{{item.nome}}</h3>
          <p>R$ {{item.preco}}</p>
        </li>
      </ul>
    </div>
</template>

<script>
import produtos from "../data/produtos.json"

export default {
  data() {
    return {
      produtos: produtos
    }
  },
}
</script>

<style scoped>
.novidadesProdutos ul {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  margin-bottom: 50px;
}

.novidadesProdutos ul li {
  padding: 5px;
  text-align: center;
}

.novidadesProdutos h3 {
  font-weight: 500;
  color: #999
}

.novidadesProdutos h3:nth-child(odd) {
  margin-top: -20px;
}

.novidadesProdutos p {
  font-weight: 500;
  color: #00002F;
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

.novidadesProdutos ul li a img:hover {
  filter: brightness(.5);
}

.novidadesProdutos img {
  width: 240px;
  height: 180px;
  margin: 0 auto;
}

@media only screen and (max-width: 768px) {
  .novidadesProdutos ul {
    flex-direction: column;
  }
}
</style>