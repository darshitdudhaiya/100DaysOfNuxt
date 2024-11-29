<template>
  <ClientOnly>
    <div
      class="flex items-center justify-center min-h-screen bg-gray-100 dark:bg-gray-700"
    >
      <div class="flex items-center justify-center py-1 text-white">
        <AnimatedCircularProgressBar :max="100" :min="0" :value="value" />
      </div>
    </div>
  </ClientOnly>
</template>

<script setup lang="ts">
import AnimatedCircularProgressBar from "../components/Progress-indicator/Animated-Progress-bar.vue";
import { ref, onMounted, onBeforeUnmount } from "vue";

const value = ref(0);

function handleIncrement(prev: number) {
  return prev === 100 ? 0 : prev + 10;
}

onMounted(() => {
  value.value = handleIncrement(value.value);
  const interval = setInterval(() => {
    value.value = handleIncrement(value.value);
  }, 2000);

  onBeforeUnmount(() => clearInterval(interval));
});
</script>
