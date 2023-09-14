<script>
import TheWelcome from '../components/TheWelcome.vue'
import { ref } from 'vue'

export default {
  components: { TheWelcome },

  setup() {
    let message = ref('Hello World')

    setTimeout(() => {
      message.value = 'Changed'
    }, 2000)
    
    return {
      message
    }
  }
}

</script>

<template>
  <main>
    <TheWelcome />
    <p><input v-model="message" type="text" /></p>
    <p>{{ message }}</p>
  </main>
</template>
