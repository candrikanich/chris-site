<template>
  <div>
    <Navigation />
    <MyResume />
  </div>
</template>

<script>
// @ is an alias to /src
import MyResume from '@/components/MyResume.vue'
import Navigation from '@/components/Navigation.vue'

export default {
  name: 'resume',
  components: {
    MyResume,
    Navigation
  }
}
</script>