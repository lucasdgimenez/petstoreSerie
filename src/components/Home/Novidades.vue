<template>
  <section id="novidades">
    <h1>Novidades</h1>
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
      </ul>
    </div>

    <div class="novidadesCategoria">
      <a href="">
        <img src="../../assets/vitolic.jpg" alt="cat">
        <h2>Para Gatos</h2>
      </a>
      <a href="" class="dog">
        <img src="../../assets/karsten.jpg" alt="dog">
        <h2>Para Cachorros</h2>
      </a>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Novidades'
}
</script>

<style scoped>

.novidadesProdutos ul {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
    background-color: seagreen;
  margin-bottom: 10px;
}

.novidadesProdutos ul li {
  background: rosybrown;
  text-align: center;
  margin-top: 5px;
  margin-right: 5px;
  margin-left: 5px;
  margin-bottom: 30px;
}

.novidadesProdutos ul li a img:hover {
  filter: brightness(.5);
}

.novidadesCategoria {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  padding-top: 10px;
}

.novidadesCategoria img, .novidadesProdutos img {
  margin: 0 auto;
}

.novidadesProdutos img {
  width: 230px;
  height: 140px;
}

.novidadesCategoria img {
  width: 450px;
  height: 200px;
}

.novidadesCategoria h2 {
  background: #dd9f0f;
  color: #fff;
  text-align: center;
  text-transform: uppercase;
  padding: 10px;
  font-size: 0.875em;
  font-weight: bold;
  position: relative;
  top: -85px;
  width: 190px;
}

</style>