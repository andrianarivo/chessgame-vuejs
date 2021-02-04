<template>
  <chessboard class="chessentry"/>
</template>

<script>
import {chessboard} from 'vue-chessboard'
import 'vue-chessboard/dist/vue-chessboard.css'

export default {
  name: 'App',
  components: {
    chessboard
  }
}
</script>

<style>

.chessentry {

  display: flex;
  width: 100vw;
  height: 100vh;
  justify-content: center;

}

</style>
