<script>
import flash from '@/mixins/flash';

export default {
  mixins: [flash]
}

</script>
<template>
  <div class="about">
    <button @click="flash('It is work on the about page!')">Click Me!</button>
  </div>
</template>

