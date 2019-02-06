<template>
  <div>
    <Navigation />
    <LandingPage />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import LandingPage from '@/components/LandingPage.vue'
import Navigation from '@/components/Navigation.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'home',
  components: {
    LandingPage,
    Navigation,
    Footer
  }
}
</script>
