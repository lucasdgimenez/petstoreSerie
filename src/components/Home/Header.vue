<template>
  <header id="header" class="container">
    <input type="text" placeholder="Pesquisar..."/>
    <a href="/">
      <img src="../../assets/logodog123.png" alt="Logo">
    </a>
    <ul>
      <li>
        <a href="">
          <img src="../../assets/user (1).png" alt="User">
        </a>
      </li>
      <li>
        <a href="">
          <img src="../../assets/shopping-cart (1).png" alt="cart">
        </a>
      </li>
    </ul>
  </header>
</template>

<script>
export default {

}
</script>

<style scoped>
#header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

#header ul {
  display: flex;
}

#header ul li {
  padding: 5px;
}

input {
  height: 20px;
  padding: 15px;
  background-image: url('../../assets/user.png') no-repeat scroll 7px 7px;
}
</style>