<script setup>
  import Header from './components/HeaderApp.vue'
  import Banner from './components/BannerApp.vue'
  import Cards from './components/CardsApp.vue'
  import Registry from './components/registryApp.vue'
  import Footer from './components/FooterApp.vue'
</script>

<template>
  <header>
    <Header></Header>
  </header>
  <main>
    <Banner></Banner>
    <Cards></Cards>
    <Registry></Registry>
    <img src="/public/img/timeline.png" alt="timeline">
    <Footer></Footer>
  </main>
</template>

<style scoped>
  img {
    display: block;
    margin: 0 auto;
  }


</style>
