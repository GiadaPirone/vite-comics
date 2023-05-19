<script >

import AppNavbar from './components/AppNavbar.vue'
import AppContent from './components/AppContent.vue'
import AppMenu from './components/AppMenu.vue'

export default {
  components:{
    AppNavbar,
    AppContent,
    AppMenu
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
  
</template>

<style scoped>
    
</style>
