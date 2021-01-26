<template>
  <section id="destaques" class="container">
    <h1 class="title_home">Destaques</h1>
    <div class="novidadesProdutos">
      <ul>
        <li>
          <a href="">
            <img src="../../assets/housedog.jpg" alt="">
          </a>
          <p>Casinha</p>
          <span>R$99.99</span>
        </li>
        <li>
          <a href="">
            <img src="../../assets/boxtransportedog.jpg" alt="">
          </a>
          <p>Caixa de transporte</p>
          <span>R$99.99</span>
        </li>
        <li>
          <a href="">
            <img src="../../assets/beddog.jpg" alt="">
          </a>
          <p>Cama</p>
          <span>R$99.99</span>
        </li>
        <li>
         <a href="">
            <img src="../../assets/balldog.jpg" alt="">
          </a>
          <p>Bola</p>
          <span>R$99.99</span>
        </li>
        <li>
         <a href="">
            <img src="../../assets/housedog.jpg" alt="">
          </a>
          <p>Casinha</p>
          <span>R$99.99</span>
        </li>

        <li>
         <a href="">
            <img src="../../assets/boxtransportedog.jpg" alt="">
          </a>
          <p>Caixa de transporte</p>
          <span>R$99.99</span>
        </li>

        <li>
         <a href="">
            <img src="../../assets/beddog.jpg" alt="">
          </a>
          <p>Cama</p>
          <span>R$99.99</span>
        </li>

        <li>
         <a href="">
            <img src="../../assets/balldog.jpg" alt="">
          </a>
          <p>Bola</p>
          <span>R$99.99</span>
        </li>
      </ul>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Destaques'
}
</script>

<style scoped>
.novidadesProdutos ul {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  margin-bottom: 20px;
}

.novidadesProdutos ul li {
  padding: 5px;
  text-align: center;
}

.novidadesProdutos p {
  font-weight: 500;
  color: #999
}

.novidadesProdutos span {
  font-weight: 500;
  color: #00002F;
}


.novidadesProdutos ul li a img:hover {
  filter: brightness(.5);
}

.novidadesProdutos img {
  width: 240px;
  height: 180px;
  margin: 0 auto;
}

@media only screen and (max-width: 600px) {
  .novidadesProdutos ul {
    flex-direction: column;
  }
}
</style>