<template>
  <section id="novidades">
    <h1>Novidades</h1>
    <div class="novidadesProdutos">
      <ul>
        <li>
          <a href="">
            <img src="../../assets/logo.png" alt="">
          </a>
          <p>Item 1</p>
          <span>R$99.99</span>
        </li>
        <li>
          <a href="">
            <img src="../../assets/logo.png" alt="">
          </a>
          <p>Item 1</p>
          <span>R$99.99</span>
        </li>
        <li>
          <a href="">
            <img src="../../assets/logo.png" alt="">
          </a>
          <p>Item 1</p>
          <span>R$99.99</span>
        </li>
        <li>
         <a href="">
            <img src="../../assets/logo.png" alt="">
          </a>
          <p>Item 1</p>
          <span>R$99.99</span>
        </li>
      </ul>
    </div>

    <div class="novidadesCategoria">
      <a href="">
        <img src="../../assets/vitolic.jpg" alt="cat">
      </a>
      <a href="" class="dog">
        <img src="../../assets/karsten.jpg" alt="dog">
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
  margin-bottom: 20px;
}

.novidadesProdutos ul li {
  background: rosybrown;
  padding: 15px;
  text-align: center;
}

.novidadesProdutos ul li a img:hover {
  background: rgba(0, 0, 0, 0.4);
}

.novidadesCategoria {
  background: tomato;
  display: flex;
}

.novidadesCategoria img {
  width: 95%;
  height: 95%;
  margin: 0 auto;
}

</style>