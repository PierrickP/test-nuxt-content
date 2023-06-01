<script setup>
const props = defineProps(["background"]);
</script>

<template>
  <div
    style="text-align: center; flex-grow: 1"
    :style="{ 'background-color': background }"
  >
    <slot></slot>
  </div>
</template>
