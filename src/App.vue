<template>
  <div id="app">
    <board /><!-- ★Boardコンポーネント呼び出し -->
  </div>
</template>

<script>

import Board from './components/Board.vue'
export default {
  name: 'App',
  components: {
    Board
  }
}
</script>

