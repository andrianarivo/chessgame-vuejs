<template>
  <section class="hero">
    <div class="hero-head">
      <nav class="navbar">
        <div class="container">
          <presentation />
        </div>
      </nav>
    </div>
    <div class="hero-body">
      <div class="container has-text-centered">
        <div class="columns">
          <div class="column is-5">
            <chessboard/>
          </div>
          <div class="column is-7">
            <!-- customize buttons here -->
          </div>
        </div>
      </div>
    </div>
    <div class="hero-foot">
      <div class="container">
        <div class="has-text-centered">
          <!-- customize texts here -->
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import { chessboard } from 'vue-chessboard'
import 'vue-chessboard/dist/vue-chessboard.css'
import Presentation from './Presentation.vue'
export default {
  components: { Presentation, chessboard }
}
</script>

<style>
.cg-board-wrap {
  margin: 0 auto;
}
</style>