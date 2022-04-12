<template>
  <div id="app">
    <Header />
    <div class="router">
      <router-view/>
    </div>
    <Footer />
  </div>
</template>

<script>
import Footer from './components/Footer.vue'
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    Header,
    Footer,
  }
}
</script>

<style>
  #app{
    min-height:100vh;
    height:auto;
  }
  .router{
    height: 85vh;
  }
</style>
