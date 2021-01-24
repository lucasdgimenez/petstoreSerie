<template>
  <nav id="menu">
    <ul>
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
nav {
  background: #8257C6;
}

nav ul {
  padding: 5px;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

nav a {
  color: #fff;
}

</style>