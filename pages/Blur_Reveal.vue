<template>
  <ClientOnly>
    <div
      class="flex items-center justify-center min-h-screen text-white bg-gray-100 dark:bg-gray-900"
    >
      <BlurReveal :delay="5" :duration="1" class="p-8">
        <h2
          class="text-3xl font-bold tracking-tighter xl:text-6xl/none sm:text-5xl"
        >
          Hey there 👋
        </h2>
        <span
          class="text-pretty text-xl tracking-tighter xl:text-4xl/none sm:text-3xl"
        >
          How is it going?
        </span>
      </BlurReveal>
    </div>
  </ClientOnly>
</template>

<script setup>
import BlurReveal from "../components/Blur-reveal/Blur_reveal.vue";
</script>
