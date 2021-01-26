<template>
  <section id="destaques" class="container">
    <h1 class="title_home">Destaques</h1>
    <div class="novidadesProdutos">
      <ul>
        <li>
          <a href="">
            <img src="../../assets/housedog.jpg" alt="">
          </a>
          <h3>Casinha</h3>
          <p>R$99.99</p>
        </li>
        <li>
          <a href="">
            <img src="../../assets/boxtransportedog.jpg" alt="">
          </a>
          <span>50% OFF</span>
          <h3>Caixa de transporte</h3>
          <p>R$99.99</p>
        </li>
        <li>
          <a href="">
            <img src="../../assets/beddog.jpg" alt="">
          </a>
          <h3>Cama</h3>
          <p>R$99.99</p>
        </li>
        <li>
         <a href="">
            <img src="../../assets/balldog.jpg" alt="">
          </a>
          <span>NOVO</span>
          <h3>Bola</h3>
          <p>R$99.99</p>
        </li>
        <li>
         <a href="">
            <img src="../../assets/housedog.jpg" alt="">
          </a>
          <h3>Casinha</h3>
          <p>R$99.99</p>
        </li>

        <li>
         <a href="">
            <img src="../../assets/boxtransportedog.jpg" alt="">
          </a>
          <h3>Caixa de transporte</h3>
          <p>R$99.99</p>
        </li>

        <li>
         <a href="">
            <img src="../../assets/beddog.jpg" alt="">
          </a>
          <h3>Cama</h3>
          <p>R$99.99</p>
        </li>

        <li>
         <a href="">
            <img src="../../assets/balldog.jpg" alt="">
          </a>
          <h3>Bola</h3>
          <p>R$99.99</p>
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