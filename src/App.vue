<script setup lang="ts">
const text = 'hello world'
const identy = 'dao12'
const color = '#44'
</script>

<template>
  <div :title="text">hi i'm a message here</div>
  <div :id="identy">this is the div for a column..</div>
  <div :style="{ color }">this page is just to tell you <span v-html="text"></span></div>
</template>

<style scoped>
#dao12 {
  color: aqua;
}
</style>
