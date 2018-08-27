<template lang="pug">
  .my-app
    v-card
      span Hello {{ name }}
</template>

<script>
export default {
  name: 'Hello',
  data() {
    return {
      name: 'world'
    }
  }
}
</script>
