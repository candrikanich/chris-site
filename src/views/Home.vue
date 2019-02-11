<template>
  <div>
    <Navigation />
    <LandingPage />
  </div>
</template>

<script>
// @ is an alias to /src
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

<style lang="less" scoped>
      nav a.router-link-exact-active {display:none;}

</style>

