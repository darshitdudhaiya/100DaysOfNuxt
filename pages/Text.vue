<template>
  <ClientOnly>
    <div
      class="flex items-center justify-center min-h-screen bg-gray-100 dark:bg-gray-900"
    >
      <div>
        <Text3d class="my-5 text-8xl font-bold max-md:text-7xl" shadow-color="red">
          3D
        </Text3d>
        <Text3d
          class="my-5 text-8xl font-black max-md:text-7xl"
          shadow-color="skyblue"
          :animate="false"
        >
          IS
        </Text3d>
        <Text3d class="my-5 text-8xl font-bold max-md:text-7xl">AWESOME</Text3d>
      </div>
    </div>
  </ClientOnly>
</template>

<script setup>
import Text3d from "../components/Text/3DText.vue";
</script>
