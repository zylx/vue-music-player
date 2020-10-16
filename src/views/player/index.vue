<template>
  <div class="container">
    <div class="play-list">playlist</div>
    <div class="player">player</div>
  </div>
</template>

<script>
export default {
  name: 'Player',
  data () {
    return {
    }
  }
}
</script>

<style lang="stylus" scoped>
.container {
  position: absolute;
  display: flex;
  height: 800px;
  width: 80%;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);

  .play-list {
    flex: 0 0 30%; /* 左侧固定200px */
    min-width: 300px;
    max-width: 380px;
    background-color: #ccffff;
  }

  .player {
    flex: 1; /* 随父级变化 */
    background-color: #ffcccc;
  }
}
</style>