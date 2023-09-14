<script setup>
import { useFlash } from '@/composables/useFlash';
let { flash } = useFlash();
</script>

<template>
  <main>
    <button @click="flash('It is work!')">Click Me!</button>
  </main>
</template>
