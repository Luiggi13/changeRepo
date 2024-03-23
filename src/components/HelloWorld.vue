<script lang="ts" setup>
import { defineProps } from "vue";
const props = defineProps<{
  msg: string;
}>();
</script>
<template>
  <div class="hello">
    <h1>{{ props.msg }}</h1>
    <p>Alpha version ready</p>
  </div>
</template>

<style scoped lang="scss"></style>
