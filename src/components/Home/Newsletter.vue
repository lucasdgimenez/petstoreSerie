<template>
  <div id="newsletter">
    <div class="vantagens container">
      <ul>
        <li>
          <img src="../../assets/icondog24.png" alt="Entrega gratuita">
          <span>Entrega gratuita a partir de R$90</span>
        </li>
        <li>
          <img src="../../assets/icondog24.png" alt="Parcelamento">
          <span>Parcelamento sem juros</span>
        </li>
        <li>
          <img src="../../assets/icondog24.png" alt="Desconto">
          <span>Cadastre-se e ganhe desconto</span>
        </li>
      </ul>
    </div>
    <div class="news">
      <h2 class="title_home">Assine nossa newsletter</h2>
      <p>Cadastre-se para receber nossas novidades e descontos exclusivos.</p>
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
  border-bottom: 3px solid #FFA100;
}

.vantagens ul li {
    padding: 5px;
  display: flex;
  align-items: center;
}

.vantagens ul li img {
    margin-right: 5px;

}

.news {
  padding: 30px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.news h2 {
  color: white;
  margin-bottom: 20px;
  font-weight: 500;
}

.news p {
  margin-bottom: 50px;
}

.news form {
  margin-top: 30px;
}

input {
  outline: 0;
  background-color: #8257C6;
  border-width: 0 0 2px;
  border-color: #CCC;
  color: white;
  margin: 5px;
  width: 250px;
  font-size: 1rem;
}

input::placeholder {
  color: #CCC;
}

button {
  background: #FEA200;
  color: #fff;
  border: none;
  padding: 10px;
  width: 80px;
  text-transform: uppercase;
}

@media only screen and (max-width: 768px) {
  .vantagens ul {
    flex-direction: column;
    align-items: center;
  }
  .news {
    text-align: center;
  }
  form {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  input {
    margin: 20px;
  }
}
</style>