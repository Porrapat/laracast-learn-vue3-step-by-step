<script setup>
  import { useStorage } from '@/composables/useStorage';

  let food = useStorage('food', 'tacos');
  let age = useStorage('age', 20);
</script>

<template>
  <main>
    <p>What's your favorite food? <input type="text" v-model="food" /></p>
    <p>What's your age? <input type="text" v-model="age" /></p>
  </main>
</template>
