<template>
  <div id="app">
    <octadesk-header></octadesk-header>

  </div>
</template>

<script>
import Menu from './components/Menu.vue'
export default {
  name: 'app',
  components: {
    'octadesk-header': Menu
  }
}
</script>
<style lang="scss" scoped>

</style>
