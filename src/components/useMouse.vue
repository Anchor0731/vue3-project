<template>
  <div>当前鼠标坐标：{{ x }} X {{ y }}</div>
</template>

<script setup>
import { useMouse } from "@vueuse/core";

const { x, y } = useMouse();
</script>

<style lang="scss" scoped></style>
