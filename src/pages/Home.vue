<template>
  <div>
    <Header/>
    <Menu/>
    <Carousel/>
    <Novidades/>
    <Destaques/>
    <Newsletter/>
  </div>
</template>

<script>
import Header from "../components/Home/Header"
import Menu from "../components/Home/Menu"
import Carousel from "../components/Home/Carousel"
import Novidades from "../components/Home/Novidades"
import Destaques from "../components/Home/Destaques"
import Newsletter from "../components/Home/Newsletter"

export default {
  name: 'Home',
  components: {
    Header, Menu, Carousel, Novidades, Destaques, Newsletter
  }
}
</script>

<style scoped>

</style>