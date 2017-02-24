<template>
  <div id="app">
    <img src="./assets/logo.png">
    <hello id="hello"></hello>
    <MyFirstVue></MyFirstVue>
  </div>
</template>

<script>
import MyFirstVue from './components/MyFirstVue'
import Hello from './components/Hello'

export default {
  name: 'app',
  components: {
    MyFirstVue,
    Hello

  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#hello {

}
</style>
