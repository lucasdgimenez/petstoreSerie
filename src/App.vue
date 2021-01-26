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
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;500&display=swap');

* {
  margin: 0; padding: 0; list-style: none; text-decoration: none;
  box-sizing: border-box;
  font-family: 'Roboto', sans-serif;
}

img {
    display: block;

}

.title_home {
  font-weight: 500;
  font-size: 1.45em;
  font-weight: bold;
  text-align: center;
  color: #999;
  text-transform: uppercase;
  line-height: 2;
  letter-spacing: 2px;

}

.container {
  max-width: 1000px;
  margin: 0 auto;
}

button {
  cursor: pointer;
}

@media only screen and (max-width: 1024px) {
  .container {
    max-width: 600px;
  }
}

@media only screen and (max-width: 768px) {
  .container {
    max-width: 300px;
  }
}

@media only screen and (max-width: 768px) {
  
}

</style>
