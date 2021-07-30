<template>
  <div id="app">
    <Header/>
    <Main/>
    <Footer/>
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap');
  *{
    font-size: 16px;
    line-height: 1.5;
    font-family: 'Poppins', sans-serif;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  body{
    color: #343A40;
    background: #E9ECEF;
  }

  .container {
    width: 100%;
    margin: 0 auto;
    padding: 0 12px;
  }

  @media (min-width: 576px) {
    .container {
      max-width: 540px;
      padding: 0;
    }
  }

  @media (min-width: 768px) {
    .container {
      max-width: 720px;
    }
  }

  @media (min-width: 992px) {
    .container {
      max-width: 960px;
    }
  }

  @media (min-width: 1200px) {
    .container {
      max-width: 1140px;
    }
  }

  @media (min-width: 1400px) {
    .container {
      max-width: 1320px;
    }
  }
  button{
    display: flex;
    border: none;
    background: transparent;
    outline: none;
    cursor: pointer;
  }
</style>
