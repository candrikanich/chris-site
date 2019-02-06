<template>
  <div>
    <Navigation />
    <Biography />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Biography from '@/components/Biography.vue'
import Navigation from '@/components/Navigation.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'about',
  components: {
    Biography,
    Navigation,
    Footer
  }
}
</script>