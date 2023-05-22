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
    AppFooter,
    
  },
  data(){
      return{
        slides: [
          {
            thumb: "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
            price: "$19.99",
            series: "Action Comics",
            type: "comic book",
          },

          {
            thumb: "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
            price: "$3.99",
            series: "American Vampire 1976",
            type: "comic book",
          },

          {
            thumb: "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
            price: "$16.99",
            series: "Aquaman",
            type: "graphic novel",
          }
        ]
      }
    }
}

</script>

<template>
  <header>
    <AppNavbar />
  </header>

  <main>
    <AppContent v-for="slide in slides"
    :img="slide.thumb"
    :bigText="slide.series" />

    <AppMenu />
  </main>

  <footer>
    <AppFooterOne />
    <AppFooter />

  </footer>
  
</template>

<style scoped>
    
</style>
