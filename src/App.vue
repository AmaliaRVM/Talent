<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Header/>
    <Talent/>

  </div>
</template>

<script>
/* import HelloWorld from './components/HelloWorld.vue' */
import Talent from './components/Talent.vue'
import Header from './components/Header.vue'

export default {
  /* name: 'app', */
  components: {
    /* HelloWorld */
    Talent,
    Header
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
  /* margin-top: 60px; */
  background-image: url("./assets/cup.jpg");
  height: 100Vh;
  margin: 0;
  
  
}
</style>
