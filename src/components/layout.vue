<template>
  <div class="layout">
    Hi {{ msg }}
    <Hello />
  </div>
</template>


<script>
import Hello from './hello.vue'
export default {
  name: 'Layout',
  components: {
    Hello,
  },
  props: {
    msg: String
  }
}
</script>
