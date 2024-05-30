<template>
  <Canvas/>
</template>

<script>
import Canvas from './components/ui/Canvas/Canvas.vue'

export default {
  name: 'App',
  components: {
    Canvas
  }
}
</script>

<style>

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  background-color: #151728;
  height: 100vh;
}
</style>