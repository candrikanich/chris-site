<template>
  <div>
    <Navigation />
    <LandingPage />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import LandingPage from '@/components/LandingPage.vue'
import Navigation from '@/components/Navigation.vue'

export default {
  name: 'home',
  components: {
    LandingPage,
    Navigation
  }
}
</script>
