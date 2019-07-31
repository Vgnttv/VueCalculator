<template>
  <div id="app">
    <Calculator/>
    <Footer/>
  </div>
</template>

<script>
import Calculator from './components/Calculator.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: {
    Calculator,
    Footer
  }
}
</script>

<style>
html { 
  background-color: #80b2e4;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 100px;
}
</style>
