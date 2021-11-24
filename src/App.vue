<template>
  <div id="app">
    <!-- header -->
    <Header />
    
    <!-- hero -->
    <Hero />

    <!-- main -->
    <Main />

    <!-- footer -->
    <Footer />
  </div>
</template>

<script>
import  Header from'@/components/Header.vue';
import Hero from'@/components/Hero.vue';
import  Main from'@/components/Main.vue';
import  Footer from'@/components/Footer.vue';


export default {
  name: 'App',
  components: {
      Header,
      Hero,
      Main,
      Footer,

  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 5px;
}
</style>
