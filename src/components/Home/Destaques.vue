<template>
  <section id="destaques">
    <h1>Destaques</h1>
    <div class="novidadesProdutos">
      <ul>
        <li>
          <a href="">
            <img src="../../assets/housedog.jpg" alt="">
          </a>
          <p>Item 1</p>
          <span>R$99.99</span>
        </li>
        <li>
          <a href="">
            <img src="../../assets/boxtransportedog.jpg" alt="">
          </a>
          <p>Item 1</p>
          <span>R$99.99</span>
        </li>
        <li>
          <a href="">
            <img src="../../assets/beddog.jpg" alt="">
          </a>
          <p>Item 1</p>
          <span>R$99.99</span>
        </li>
        <li>
         <a href="">
            <img src="../../assets/balldog.jpg" alt="">
          </a>
          <p>Item 1</p>
          <span>R$99.99</span>
        </li>
        <li>
         <a href="">
            <img src="../../assets/housedog.jpg" alt="">
          </a>
          <p>Item 1</p>
          <span>R$99.99</span>
        </li>

        <li>
         <a href="">
            <img src="../../assets/boxtransportedog.jpg" alt="">
          </a>
          <p>Item 1</p>
          <span>R$99.99</span>
        </li>

        <li>
         <a href="">
            <img src="../../assets/beddog.jpg" alt="">
          </a>
          <p>Item 1</p>
          <span>R$99.99</span>
        </li>

        <li>
         <a href="">
            <img src="../../assets/balldog.jpg" alt="">
          </a>
          <p>Item 1</p>
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
  background: crimson;
  flex-wrap: wrap;
}

.novidadesProdutos ul li {
  background: rosybrown;
  padding: 5px;
  text-align: center;
}

.novidadesProdutos ul li a img:hover {
  background: rgba(0, 0, 0, 0.4);
}

.novidadesCategoria img, .novidadesProdutos img {
  width: 230px;
  height: 150px;
  margin: 0 auto;
}
</style>