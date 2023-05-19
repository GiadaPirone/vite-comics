<script >

import AppNavbar from './components/AppNavbar.vue'
import AppContent from './components/AppContent.vue'
import AppMenu from './components/AppMenu.vue'
import AppFooterOne from './components/AppFooterOne.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  components:{
    AppNavbar,
    AppContent,
    AppMenu,
    AppFooterOne,
    AppFooter
  }
}
</script>

<template>
  <header>
    <AppNavbar />
  </header>

  <main>
    <AppContent />
    <AppMenu />
  </main>

  <footer>
    <AppFooterOne />
    <AppFooter />

  </footer>
  
</template>

<style scoped>
    
</style>
