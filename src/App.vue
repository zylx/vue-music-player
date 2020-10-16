<template>
  <div id="app">
    <player />
  </div>
</template>

<script>
import Player from './views/player/'

export default {
  name: 'App',
  components: {
    Player
  }
}
</script>

<style lang="stylus">
html, body {
  width: 100%;
  height: 100%;
  margin: 0;
  padding: 0;
  background-color: #fefefe;
}
</style>
