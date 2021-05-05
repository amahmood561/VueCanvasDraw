<template>
  <div id="app">
    <h1>Drawing with mousemove event</h1>
    <canvas id="myCanvas" width="560" height="360" />
  </div>
</template>

<script lang="ts">
import {canvas} from "./canvas";
export default canvas;
</script>

<style scoped>
#myCanvas {
  border: 1px solid grey;
}
</style>