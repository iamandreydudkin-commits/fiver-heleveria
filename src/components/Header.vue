<script setup>
import Instragram from "@/components/icons/Instagram.vue";
import Youtube from "@/components/icons/Youtube.vue";
import Tiktok from "@/components/icons/Tiktok.vue";
</script>

<template>
  <div class="z-30 fixed top-0 w-full bg-primary text-white">
    <div class="pt-5 max-w-7xl flex justify-between items-center mx-auto">
      <div>
        <img src="/logo.png" width="80" alt="" />
      </div>
      <div class="flex gap-x-[60px]">
        <a href="#">ГОЛОВНА</a>
        <a href="#">КОНТАКТИ</a>
        <a href="#">ПРО МЕНЕ</a>
      </div>
      <div class="flex gap-x-4">
        <div
          class="w-8 h-8 bg-white flex justify-center items-center rounded-full"
        >
          <Instragram />
        </div>
        <div
          class="w-8 h-8 bg-white flex justify-center items-center rounded-full"
        >
          <Youtube />
        </div>
        <div
          class="w-8 h-8 bg-white flex justify-center items-center rounded-full"
        >
          <Tiktok />
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="postcss" scoped>
a {
  @apply hover:bg-slate-800 hover:text-white px-5 py-3 rounded-md;
}
</style>
