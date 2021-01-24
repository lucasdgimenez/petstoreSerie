<template>
  <div id="newsletter">
    <div class="vantagens">
      <ul>
        <li>
          <i class="fas fa-user"></i>
          <span>Entrega gratuita a partir de R$90</span>
        </li>
        <li>
          <i class="fas fa-user"></i>
          <span>Parcelamento sem juros</span>
        </li>
        <li>
          <i class="fas fa-user"></i>
          <span>Cadastre-se e ganhe desconto</span>
        </li>
      </ul>
    </div>
    <div class="news">
      <h2>Assine nossa newsletter</h2>
      <p>The flex-wrap property specifies whether the flexible items should wrap or not.</p>
      <form>
        <input placeholder="Nome" type="text">
        <input placeholder="E-mail" type="email">
        <button @click="preventDefault()">Enviar</button>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Newsletter'
}
</script>

<style scoped>
#newsletter {
  background: #8257C6;
  color: #fff;
}

.vantagens ul {
  display: flex;
  padding: 15px;
  justify-content: space-around;
  border-bottom: 4px solid #FFA100;
}

.vantagens ul li {
  padding: 5px;
}

.news {
  padding: 30px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

button {
  background: #FEA200;
  color: #fff;
  border: none;
  padding: 10px;
}
</style>