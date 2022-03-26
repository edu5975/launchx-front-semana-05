<template>
    <nav-bar/>
    <router-view/>
    <footer-pag/>
</template>

<script>
  import FooterPag from '@/components/FooterPag.vue'
  import NavBar from '@/components/NavBar.vue'

  export default {
    name: 'App',
    components: {
      NavBar,
      FooterPag
    }
  }
</script>

<style>
</style>
