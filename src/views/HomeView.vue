<script setup>
import TheWelcome from '../components/TheWelcome.vue'
import { ref } from 'vue'

let message = ref('Hello World')

setTimeout(() => {
  message.value = 'Changed'
}, 2000)
</script>

<template>
  <main>
    <TheWelcome />
    <p><input v-model="message" type="text" /></p>
    <p>{{ message }}</p>
  </main>
</template>
