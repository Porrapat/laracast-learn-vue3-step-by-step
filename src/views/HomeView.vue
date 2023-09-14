<script>

import flash from '@/mixins/flash';

export default {
  mixins: [flash]
}

</script>

<template>
  <main>
    <button @click="flash('It is work!')">Click Me!</button>
  </main>
</template>
