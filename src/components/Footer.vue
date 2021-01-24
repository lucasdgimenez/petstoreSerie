<template>
  <footer class="footer">
      <div class="pet">
        <img src="../assets/logo.png" alt="Pet">
        <ul class="socialMedia">
          <li>
            <a href="https://www.facebook.com">
              <i class="fab fa-facebook"></i>
            </a>
          </li>
          <li>
            <a href="https://www.instagram.com">
              <i class="fab fa-instagram-square"></i>
            </a>
          </li>
          <li>
            <a href="https://www.twitter.com">
              <i class="fab fa-twitter"></i>
            </a>
          </li>
        </ul>
        <ul>
          <li>
            2019 - CNPJ 71.687.760/0001-67
          </li>
          <li>
            Rua Chris Haní, 538 - Campinas, SP
          </li>
        </ul>
      </div>

      <div class="petstore">
        <h5>PET STORE</h5>
        <ul>
          <li>
            <a href="">Quem somos</a>
          </li>
          <li>
            <a href="">Como comprar</a>
          </li>
          <li>
            <a href="">Trocas e devoluções</a>
          </li>
          <li>
            <a href="">Frete e Entregas</a>
          </li>
        </ul>
      </div>

      <div class="contato">
        <h5>Contato</h5>
        <ul>
          <li>(99) 9999-9999</li>
          <li>(99) 9999-9999</li>
          <li>petstore@petstore.com.br</li>
        </ul>
      </div>
      
      <div class="pagamento">
        <h5>Pagamento</h5>
        <ul>
          <li>
            <img src="../assets/visa.png" alt="Visa">
          </li>
          <li>
            <img src="../assets/mastercard.png" alt="Mastercard">
          </li>
          <li>
            <img src="../assets/american-express.png" alt="American express">
          </li>
          <li>
            <img src="../assets/paypal.png" alt="Paypal">
          </li>
        </ul>
        <ul>
          <li>
            <img src="../assets/visa.png" alt="Visa">
          </li>
          <li>
            <img src="../assets/mastercard.png" alt="Mastercard">
          </li>
          <li>
            <img src="../assets/american-express.png" alt="American express">
          </li>
          <li>
            <img src="../assets/paypal.png" alt="Paypal">
          </li>
        </ul>
      </div>

  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style scoped>
.footer {
  display: flex;
}

.pet {
  display: flex;
  flex-direction: column;
  background: darkgoldenrod;
}

.pet img {
  width: 40%;
}

.socialMedia {
  display: flex;
  justify-content: space-around;
}

.pagamento ul {
  display: flex;
}

.pagamento ul li {
  padding: 5px;
}
</style>