<template>
  <Canvas/>
  <Controls
      @add-square="addSquare"
      @add-circle="addCircle"
  />
</template>

<script>
import Canvas from "./components/Canvas.vue";
import Controls from "./components/Controls.vue";

export default {
  components: {Canvas, Controls},
  methods: {
    addSquare() {
      // call "drawSquare" method on canvas
    },
    addCircle() {
      // call "drawCircle" method on canvas
    }
  }
}
</script>
