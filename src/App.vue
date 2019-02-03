<template>
  <div id="app">
    <micky-watch/>
  </div>
</template>

<script>
import MickyWatch from './components/MickyWatch.vue'

export default {
  name: 'app',
  components: {
    MickyWatch
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  background: #000;
  height:100vh;
}
</style>
