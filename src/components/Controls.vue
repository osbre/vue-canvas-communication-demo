<template>
  <br><br><br>
  <button @click="$emit('add-square')">Add square</button>
  <button @click="$emit('add-square')">Add circle</button>
</template>

<script>
export default {
  name: "Controls",
  emits: ['add-square', 'add-circle'],
}
</script>
