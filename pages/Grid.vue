<template>
  <ClientOnly>
    <div
      class="flex items-center justify-center min-h-screen bg-gray-100 dark:bg-gray-900"
    >
      <div class="flex items-center justify-center p-4">
        <AnimateGrid :cards="cards">
          <template #logo="{ logo }">
            <img class="logo mx-auto h-20 w-auto " :src="logo" />
          </template>
        </AnimateGrid>
      </div>
    </div>
  </ClientOnly>
</template>

<script setup>
import AnimateGrid from "../components/Grid/AnimateGrid.vue";
import cloudflare from "../assets/svgs/cloudflare-icon.svg";

const cards = Array.from({ length: 16 }, () => ({
  logo: cloudflare,
}));
</script>
