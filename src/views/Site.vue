<template>
  <div>
    <Navigation />
    <ProjectStatus />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import ProjectStatus from '@/components/ProjectStatus.vue'
import Navigation from '@/components/Navigation.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'site',
  components: {
    ProjectStatus,
    Navigation,
    Footer
  }
}
</script>