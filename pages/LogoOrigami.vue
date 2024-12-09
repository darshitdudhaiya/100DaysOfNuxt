<template>
  <div
    class="flex h-72 flex-col items-center justify-center gap-12 bg-background px-4 py-24 md:flex-row"
  >
    <LogoOrigami>
      <LogoOrigamiItem class="bg-orange-300 text-neutral-900">
        <GitHubIcon />
      </LogoOrigamiItem>
      <LogoOrigamiItem class="bg-green-300 text-neutral-900">
        <NotionIcon />
      </LogoOrigamiItem>
      <LogoOrigamiItem class="bg-blue-300 text-neutral-900">
        <ZapierIcon />
      </LogoOrigamiItem>
      <LogoOrigamiItem class="bg-white text-black">
        <MessengerIcon />
      </LogoOrigamiItem>
      <LogoOrigamiItem class="bg-purple-300 text-neutral-900">
        <GoogleDocsIcon />
      </LogoOrigamiItem>
    </LogoOrigami>
  </div>
</template>

<script setup>
import GitHubIcon from "../assets/icons/GitHubIcon.vue";
import NotionIcon from "../assets/icons/NotionIcon.vue";
import ZapierIcon from "../assets/icons/ZapierIcon.vue";
import MessengerIcon from "../assets/icons/MessengerIcon.vue";
import GoogleDocsIcon from "../assets/icons/GoogleDocsIcon.vue";
import LogoOrigamiItem from "~/components/Logo-origami/LogoOrigamiItem.vue";
</script>
