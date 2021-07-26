<template>
  <div id="app">
    <Header/>
    <Main/>
    <Footer/>
    <FooterNav/>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Main from '@/components/Main.vue'
import Footer from "@/components/Footer.vue"
import FooterNav from "@/components/FooterNav.vue";

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer, 
    FooterNav
  }
}
</script>

<style lang="scss">
</style>
