<template>
    <ClientOnly>
      <div class="flex items-center justify-center min-h-screen bg-gray-100 dark:bg-gray-900">
        <CardContainer>
          <CardBody
            class="group/card relative w-full max-w-md rounded-lg border border-gray-300 bg-white p-6 shadow-lg transition-all duration-300 hover:scale-105 hover:shadow-xl dark:border-gray-700 dark:bg-gray-800 dark:hover:shadow-emerald-500/[0.2]"
          >
            <!-- Card Title -->
            <CardItem
              :translate-z="50"
              class="text-2xl font-bold text-gray-800 dark:text-white"
            >
              Make Things Float in Air
            </CardItem>
  
            <!-- Card Description -->
            <CardItem
              as="p"
              translate-z="60"
              class="mt-2 text-sm text-gray-600 dark:text-gray-400"
            >
              Hover over this card to unleash the power of CSS perspective.
            </CardItem>
  
            <!-- Card Image -->
            <CardItem
              :translate-z="100"
              class="mt-4 w-full"
            >
              <NuxtImg
                src="https://images.unsplash.com/photo-1441974231531-c6227db76b6e?q=80&w=2560&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                height="1000"
                width="1000"
                class="h-48 w-full rounded-md object-cover transition-transform duration-300 group-hover/card:scale-105 group-hover/card:shadow-lg"
                alt="thumbnail"
              />
            </CardItem>
  
            <!-- Card Actions -->
            <div class="mt-8 flex items-center justify-between">
              <!-- Link -->
              <CardItem
                :translate-z="20"
                as="a"
                href="https://rahulv.dev"
                target="__blank"
                class="rounded-md px-4 py-2 text-xs font-medium text-blue-600 transition-colors hover:text-blue-800 dark:text-emerald-400 dark:hover:text-emerald-600"
              >
                Visit →
              </CardItem>
              <!-- Button -->
              <CardItem
                :translate-z="20"
                as="button"
                class="rounded-md bg-blue-600 px-4 py-2 text-xs font-semibold text-white transition-transform hover:scale-110 hover:bg-blue-700 dark:bg-emerald-500 dark:hover:bg-emerald-600"
              >
                Get Started
              </CardItem>
            </div>
          </CardBody>
        </CardContainer>
      </div>
    </ClientOnly>
  </template>
  
  <script setup>
  import CardContainer from "../components/Card/CardContainer.vue";
  import CardItem from "../components/Card/CardItem.vue";
  import CardBody from "../components/Card/CardBody.vue";

  </script>
  