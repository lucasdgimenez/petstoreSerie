<template>
  <nav id="menu">
    <ul class="container" v-if="!modoMobile">
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
    </ul>

      <div class="menuMobile">
        <a href="" @click.prevent="mobile">
          <img src="../../assets/menu.png" alt="Menu">
        </a>
      </div>
  </nav>
</template>

<script>
export default {
  name: 'Menu',
  data() {
    return {
      modoMobile: false
    }
  },
  methods: {
    mobile() {
      this.modoMobile = !this.modoMobile;
    }
  }
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

#menu ul li {
  padding: 5px;
}

#menu ul li a {
  color: #fff;
  padding: 5px;
}

#menu ul li a:hover {
    background-color: white;
    color: #8257C6;
  }

.menuMobile {
  display: none;
}

@media only screen and (max-width: 768px) {
  #menu ul {
    flex-direction: column;
    align-items: center;
  }
  #menu ul li {
    margin-bottom: 10px;
  }
  #menu ul li a {
    padding: 5px;
  }
  .menuMobile {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}

</style>