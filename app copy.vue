<template>
  <div
    class="flex items-center justify-center min-h-screen bg-gray-200 dark:bg-gray-800 transition-colors duration-300"
  >
    <div class=" p-6 space-y-6 text-center">
      <!-- Uncomment components as needed -->
      <!-- Each component will now take the full width -->
      <!-- <Card /> -->
      <!-- <Text /> -->
      <!-- <Grid /> -->
      <!-- <Progressbar /> -->
      <!-- <List /> -->
      <!-- <Slider /> -->
      <!-- <AutoPlayCompare /> -->
      <!-- <DragHandleCompare /> -->
      <!-- <Compare /> -->
      <!-- <BlurReveal /> -->
      <!-- <BoxReveal /> -->
      <!-- ConfettiDefault Component -->
      <!-- <div>
        <h2
          class="text-4xl font-semibold text-gray-700 dark:text-gray-300 mb-36"
        >
          Confetti Default
        </h2>
        <ConfettiDefault />
      </div> -->

      <!-- BasicConfetti Component -->
      <!-- <div>
        <h2
          class="text-4xl font-semibold text-gray-700 dark:text-gray-300 mb-36 mt-64"
        >
          Basic Confetti
        </h2>
        <BasicConfetti />
      </div> -->

      <!-- RandomDirectionConfetti Component -->
      <!-- <div>
        <h2
          class="text-4xl font-semibold text-gray-700 dark:text-gray-300 mb-36 mt-64"
        >
          Random Direction Confetti
        </h2>
        <RandomDirectionConfetti />
      </div>
 -->
      <!-- FireworksConfetti Component -->
      <!-- <div>
        <h2
          class="text-4xl font-semibold text-gray-700 dark:text-gray-300 mb-36 mt-64"
        >
          Fireworks Confetti
        </h2>
        <FireworksConfetti />
      </div> -->

      <!-- SideCannonConfetti Component -->
      <!-- <div class="pb-60">
        <h2
          class="text-4xl font-semibold text-gray-700 dark:text-gray-300 mb-36 mt-64"
        >
          Side Cannon Confetti
        </h2>
        <SideCannonConfetti />
      </div> -->

      <!-- <ParticleWhirlpool /> -->
      <!-- <Lamp /> -->
      <LinkPreview />
    </div>
  </div>
</template>

<script setup>
// Import all components
import Card from "./pages/Card";
import Text from "./pages/Text";
import Grid from "./pages/Grid";
import Progressbar from "./pages/Progress-bar";
import List from "./pages/List";
import Slider from "./pages/Slider";
import BlurReveal from "./pages/Blur_Reveal.vue";
import BoxReveal from "./pages/BoxReveal.vue";
import AutoPlayCompare from "./pages/AutoplayCompare.vue";
import DragHandleCompare from "./pages/DragHandleCompare.vue";
import Compare from "./pages/Compare.vue";
import ConfettiDefault from "./pages/ConfettiDefault.vue";
import BasicConfetti from "./pages/BasicConfetti.vue";
import RandomDirectionConfetti from "./pages/RandomDirectionConfetti.vue";
import SideCannonConfetti from "./pages/SideCannonConfetti.vue";
import FireworksConfetti from "./pages/FireworksConfetti.vue";
import ParticleWhirlpool from "./pages/ParticleWhirlpool.vue";
import Lamp from "./pages/Lamp.vue";
import Lens from "./pages/Lens.vue";
import LinkPreview from "./pages/LinkPreview.vue";
</script>
