<script setup lang="ts">
withDefaults(
  defineProps<{
    msg: string;
  }>(),
  {
    msg: "ok",
  }
);
</script>

<template>
  <div>{{ msg }}, {{ msg.length }}</div>
</template>
