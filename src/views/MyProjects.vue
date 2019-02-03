<template>
  <div class="projects">
    <h1>This is a projects page</h1>
    <Projects />
  </div>
</template>

<script>
// @ is an alias to /src
import Projects from '@/components/Projects.vue'

export default {
  name: 'projects',
  components: {
    Projects
  }
}
</script>