<template>
  <section id="destaques">
    <h1>Destaques</h1>
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
  justify-content: space-between;
  margin-bottom: 20px;
  background: crimson;
  flex-wrap: wrap;
}

.novidadesProdutos ul li {
  background: rosybrown;
  padding: 15px;
  text-align: center;
}

.novidadesProdutos ul li a img:hover {
  background: rgba(0, 0, 0, 0.4);
}
</style>