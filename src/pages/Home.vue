<template>
  <div>
    <Header/>
    <Menu/>
    <Carousel/>
    <Opcoes/>
    <Novidades/>
    <Destaques/>
    <Newsletter/>
    <Footer/>
  </div>
</template>

<script>
import Header from "../components/Home/Header"
import Menu from "../components/Home/Menu"
import Carousel from "../components/Home/Carousel"
import Novidades from "../components/Home/Novidades"
import Destaques from "../components/Home/Destaques"
import Newsletter from "../components/Home/Newsletter"
import Opcoes from "../components/Home/Opcoes"
import Footer from "../components/Footer"

export default {
  name: 'Home',
  components: {
    Header, Menu, Carousel, Novidades, Destaques, Newsletter, Opcoes, Footer
  }
}
</script>

<style scoped>

</style>