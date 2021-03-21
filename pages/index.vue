<template>
  <div id="index">
    {{ message }}
  </div>
</template>

<script>
import { defineComponent, ref } from '@nuxtjs/composition-api'
export default defineComponent({
  setup () {
    const message = ref('')
    return { message }
  },
  head: {}
})
</script>

<style lang="scss">
#index {
  cursor: inherit;
}
</style>
