<script >

import AppNavbar from './components/AppNavbar.vue'
import AppContent from './components/AppContent.vue'
// import AppContent from `./components/AppContent.vue`

export default {
  components:{
    AppNavbar,
    AppContent
  }
}
</script>

<template>
  <header>
    <AppNavbar />
  </header>
  <main>
    <AppContent />
  </main>
  
</template>

<style scoped>
    
</style>
