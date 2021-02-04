<template>
  <Counter :initialValue="initialValue"/>
</template>

<script>
import Counter from './components/Counter'

export default {
  components: {
    Counter
  },
  data() {
      return {
          initialValue: 10
      }
  }
}
</script>

<style>
</style>
