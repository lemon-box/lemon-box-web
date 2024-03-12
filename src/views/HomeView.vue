<template>
  <div>
    <button @click="exit">123123</button>
    <button @click="exit2">app1.exit</button>
  </div>
</template>

<script setup lang="ts">
function exit() {
  // @ts-ignore
  window.lemon.application.exit()
}
function exit2() {
  // @ts-ignore
  window.app1.exit()
}
</script>
