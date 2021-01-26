<template>
  <footer class="footer">
    <div class="first_footer container">
         <div class="pet">
          <img src="../assets/logodog123.png" alt="Pet">
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
           
            <a href="https://wa.me/5511985974862" style="position:fixed;width:60px;height:60px;bottom:40px;right:40px;background-color:#25d366;color:#FFF;border-radius:50px;text-align:center;font-size:30px;box-shadow: 1px 1px 2px #888;
            z-index:1000;" target="_blank">
              <i style="margin-top:16px" class="fab fa-whatsapp"></i>
            </a>
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
            <h5>CONTATO</h5>
            <ul>
              <li>(99) 9999-9999</li>
              <li>(99) 9999-9999</li>
              <li>petstore@petstore.com.br</li>
            </ul>
          </div>
        
          <div class="pagamento">
            <h5>PAGAMENTO</h5>
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
      </div>
     
      
    <div id="second_footer">
      <div class="container">
        <p>TECNOLOGIA E DESENVOLVIMENTO. </p>
        <a href="https://seriedesign.com.br/" target="_blank">
          <img src="../assets/icondog24.png" alt="Serie Design">
        </a>
      </div>
       
      
    </div>

  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style scoped>
.first_footer {
  display: flex;
  flex-wrap: wrap;
}

.first_footer {
  margin-top: 20px;
  display: flex;
  justify-content: space-between;
}

.pet {
  display: flex;
  flex-direction: column;
  align-items: center;
    color: #999;
}

.pet img {
  width: 40%;
}

.pet ul li {
  margin: 5px;
}

.pet ul:last-child {
  margin-bottom: 30px;
}

.socialMedia {
  display: flex;
  justify-content: space-around;
}

.socialMedia i {
  font-size: 24px;
  background: #999;
  border-radius: 50%;
  padding: 5px;
  color: white;
  margin: 10px;
}

.socialMedia i:hover {
  background: #FEA200;
}

.petstore ul li a, .contato ul li {
  color: #999;
}

.petstore ul li a:hover {
  text-decoration: underline;
}

.petstore ul li, .contato ul li, .petstore h5, .contato h5,
.pagamento h5 {
  margin: 10px;
}

.pagamento ul li {
  margin: 5px;
}

.pagamento ul {
  display: flex;
}

#second_footer {
  background: #CCC;
  padding: 20px;
}

#second_footer div {
  display: flex;
  justify-content: center;
  align-items: center;
}

@media only screen and (max-width: 768px) {
  .first_footer {
    flex-direction: column;
    align-items: center;
  }
  .first_footer div {
    margin-bottom: 15px;
  }
}
</style>