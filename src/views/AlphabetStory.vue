<template>
  <div class="alphabet">
    <h1>This is a the Alphabet Story page</h1>
    <Alphabet />
  </div>
</template>

<script>
// @ is an alias to /src
import Alphabet from '@/components/Alphabet.vue'

export default {
  name: 'alphabet',
  components: {
    Alphabet
  }
}
</script>