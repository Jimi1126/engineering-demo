<script setup lang="ts">
defineProps<{
  msg: string
}>()
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
