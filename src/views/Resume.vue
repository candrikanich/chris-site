<template>
  <div>
    <Navigation />
    <MyResume />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import MyResume from '@/components/MyResume.vue'
import Navigation from '@/components/Navigation.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'resume',
  components: {
    MyResume,
    Navigation,
    Footer
  }
}
</script>