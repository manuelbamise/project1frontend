<script setup lang="ts">
const text = 'hello world'
const identy = 'dao12'

</script>

<template>
  <div :id="identy">this is the div for a column..</div>
  <div>this page is just to tell you <span v-html="text"></span></div>
</template>

<style scoped>
#dao12 {
  color: aqua;
}
</style>
