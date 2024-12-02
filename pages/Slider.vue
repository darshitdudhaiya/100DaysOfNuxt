<template>
  <ClientOnly>
    <div
      class="flex items-center justify-center min-h-screen bg-gray-100 dark:bg-gray-900"
    >
      <div class="w-full p-4">
        <BalanceSlider
          :right-color="rightColor"
          left-content="COFFEE"
          right-content="MILK"
          :indicator-color="indicatorColor"
        />
      </div>
    </div>
  </ClientOnly>
</template>

<script lang="ts" setup>
import { useColorMode } from "@vueuse/core";
import BalanceSlider from "~/components/Slider/BalanceSlider.vue";

const isDark = computed(() => useColorMode().value == "dark");
const rightColor = computed(() => (isDark.value ? "#FFFFFF" : "#000000"));
const indicatorColor = computed(() => (isDark.value ? "#FFFFFF" : "#000000"));
</script>
