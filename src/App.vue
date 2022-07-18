<template>
  <div id="app">
    <Header />
    <Products />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';
import Products from './components/Products.vue';

export default {
  name: 'App',
  components: {
    Header,
    Products,
    Main,
    Footer
  }
}
</script>

<style lang="scss">
@import '~bootstrap/scss/bootstrap.scss';
@import './styles/general.scss';
@import './styles/variables.scss';
</style>
