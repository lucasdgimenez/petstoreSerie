<template>
  <div id="app">
    <Home/>
  </div>
</template>

<script>
import Home from './pages/Home.vue'

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
* {
  margin: 0; padding: 0; list-style: none; text-decoration: none;
}

img {
  display: block;
}

#app div {
  max-width: 1000px;
  margin: 0 auto;
}
</style>
