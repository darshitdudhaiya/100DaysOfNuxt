<template>
  <div
    class="size-full max-w-lg items-center justify-center overflow-hidden p-8"
  >
    <!-- Title with Reveal Effect -->
    <BoxReveal color="#E1251B">
      <p class="text-[3.5rem] font-semibold">
        100 Days of Vue<span class="text-[#E1251B]">.</span>
      </p>
    </BoxReveal>

    <!-- Subtitle with Reveal Effect -->
    <BoxReveal color="#E1251B" :duration="1">
      <h2 class="mt-[.5rem] text-[1rem]">
        Day 70: Animated Box Reveal
      </h2>
    </BoxReveal>

    <!-- Description with Reveal Effect -->
    <BoxReveal color="#E1251B" :duration="2">
      <p class="mt-6">
        🎉 Built with <span class="text-[#E1251B]">Vue/Nuxt</span>,  
        <span class="text-[#E1251B]">TypeScript</span>, and  
        <span class="text-[#E1251B]">Tailwind CSS</span>.  
        🚀 70 days in, 30 to go—exploring the power of Vue every day!
      </p>
    </BoxReveal>
  </div>
</template>
