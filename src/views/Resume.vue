<template>
  <div class="resume">
    <h1>This is a resume page</h1>
    <MyResume />
  </div>
</template>

<script>
// @ is an alias to /src
import MyResume from '@/components/MyResume.vue'

export default {
  name: 'resume',
  components: {
    MyResume
  }
}
</script>