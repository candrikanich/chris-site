<template>
  <div class="resume">
    <h1>This is a resume page</h1>
    <Resume />
  </div>
</template>

<script>
// @ is an alias to /src
import Resume from '@/components/Resume.vue'

export default {
  name: 'resume',
  components: {
    Resume
  }
}
</script>