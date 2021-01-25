<template>
  <nav id="menu">
    <ul class="container">
      <li>
        <a href="">Caes</a>
      </li>
      <li>
        <a href="">Gatos</a>
      </li>
      <li>
        <a href="">Passaros</a>
      </li>
      <li>
        <a href="">Peixes</a>
      </li>
      <li>
        <a href="">Promoções</a>
      </li>
      <li>
        <a href="">Medicamentos</a>
      </li>
      <li>
        <a href="">Antipulgas</a>
      </li>
      <li>
        <a href="">
          <img src="../../assets/menu.png" alt="Menu">
        </a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'Menu'
}
</script>

<style>
#menu {
  background: #8257C6;
  padding: 5px;
}

#menu ul {
  display: flex;
  justify-content: space-around;
  align-items: center;
}

#menu ul li a {
  color: #fff;
}

</style>