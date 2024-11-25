<template>
    <div
      :class="cn('h-96 w-96', $props.class)"
      style="transform-style: preserve-3d"
    >
      <slot />
    </div>
  </template>
  
  <script setup lang="ts">
  import { cn } from "../../Lib/utils.js";
  
  const props = defineProps({
    class: String,
  });
  </script>