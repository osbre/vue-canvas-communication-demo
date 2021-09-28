<template>
  <canvas ref="canvas" style="border: #42b983 solid 4px"></canvas>
</template>

<script>
export default {
  name: "Canvas",
  data: () => {
    return {
      ctx: null,
    }
  },
  mounted() {
    this.ctx = this.$refs.canvas.getContext('2d');
  },
  methods: {
    drawSquare(options = {x: 25, y: 25, w: 100, h: 100}) {
      this.ctx.fillRect(options.x, options.y, options.w, options.h); // demo purpose
    },
    drawCircle(options = {x: 25, y: 25, w: 200, h: 100}) {
      this.ctx.fillRect(options.x, options.y, options.w, options.h); // demo purpose
    },
    drawText(options = {x: 25, y: 25, w: 300, h: 100}) {
      this.ctx.fillRect(options.x, options.y, options.w, options.h); // demo purpose
    },
  }
}
</script>
