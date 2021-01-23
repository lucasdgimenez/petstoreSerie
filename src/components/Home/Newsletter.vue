<template>
  <div id="newsletter">
    <div class="vantagens">
      <ul>
        <li>
          <span>Entrega gratuita a partir de R$90</span>
        </li>
        <li>
          <span>Parcelamento sem juros</span>
        </li>
        <li>
          <span>Cadastre-se e ganhe desconto</span>
        </li>
      </ul>
    </div>
    <div class="news">
      <h3>Assine nossa newsletter</h3>
      <p>The flex-wrap property specifies whether the flexible items should wrap or not.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Newsletter'
}
</script>

<style>
#newsletter {
  background: #923bc4;
  color: #fff;
}

.vantagens ul {
  display: flex;
  padding: 15px;
  justify-content: space-around;
  border-bottom: 4px solid yellow;
}
</style>