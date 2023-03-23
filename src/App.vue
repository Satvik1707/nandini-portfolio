<template>
  <div id="app">
    <router-view />
    <footer>
      <Bee />
    </footer>
  </div>
</template>

<script>
import Bee from '~/components/Bee.vue'

export default {
  components: {
    Bee
  }
}
</script>

<style>

</style>