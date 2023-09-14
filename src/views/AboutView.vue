<script setup>
import { useFlash } from '@/composables/useFlash';
let { flash } = useFlash();
</script>

<template>
  <div class="about">
    <button @click="flash('It is work on the about page!')">Click Me!</button>
  </div>
</template>

