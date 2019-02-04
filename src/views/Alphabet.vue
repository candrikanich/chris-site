<template>
  <div class="alphabet">
    <h1>This is a the Alphabet Story page</h1>
    <AlphabetStory />
  </div>
</template>

<script>
// @ is an alias to /src
import AlphabetStory from '@/components/AlphabetStory.vue'

export default {
  name: 'alphabet',
  components: {
    AlphabetStory
  }
}
</script>