<template>
  <div class="flex w-full justify-center">
    <Compare slide-mode="drag" class="rounded-xl !bg-zinc-950">
      <template #first-content>
        <div class="size-full overflow-auto bg-zinc-900 p-8">
          <pre class="font-mono text-red-400">{{ firstCode }}</pre>
        </div>
      </template>
      <template #second-content>
        <div class="size-full overflow-auto bg-zinc-900 p-8">
          <pre class="font-mono text-green-400">{{ secondCode }}</pre>
        </div>
      </template>
    </Compare>
  </div>
</template>

<script setup lang="ts">
const firstCode = `function greet() {
    console.log("Hello, World!");
  }`;

const secondCode = `function greet() {
    console.log("Hello, World!");
  }`;
</script>
