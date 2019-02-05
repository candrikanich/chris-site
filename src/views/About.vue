<template>
  <div>
    <Navigation />
    <Biography />
  </div>
</template>

<script>
// @ is an alias to /src
import Biography from '@/components/Biography.vue'
import Navigation from '@/components/Navigation.vue'

export default {
  name: 'about',
  components: {
    Biography,
    Navigation
  }
}
</script>