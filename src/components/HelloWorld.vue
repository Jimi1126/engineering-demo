<script setup lang="ts">
defineProps<{
  msg: string
}>()

const a = 0
</script>

<template>
  <div class="greetings">
    <h1 :class="$style.blue">{{ msg }}</h1>
  </div>
</template>

<style module>
blue {
  color: blue;
}
</style>
