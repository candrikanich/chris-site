<template>
  <div class="projects">
    <h1>This is a projects page</h1>
    <MyProjects />
  </div>
</template>

<script>
// @ is an alias to /src
import MyProjects from '@/components/MyProjects.vue'

export default {
  name: 'projects',
  components: {
    MyProjects
  }
}
</script>