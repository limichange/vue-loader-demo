<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div class="logo"></div>
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style lang="css" scoped>
.logo {
  background: url('./assets/logo.png');
  width: 200px;
  height: 200px;
}
</style>


<style lang="css" module>
.logo {
  /* error To install it, you can run: npm install --save assets/logo.png */
  /* background: url('./assets/logo.png'); */
  width: 200px;
  height: 200px;
}
</style>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
