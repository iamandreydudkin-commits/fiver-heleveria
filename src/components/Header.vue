<script setup>
import Instragram from "@/components/icons/Instagram.vue";
import Youtube from "@/components/icons/Youtube.vue";
import Tiktok from "@/components/icons/Tiktok.vue";
import Hamburger from "@/components/icons/Hamburger.vue";
import { ref } from "vue";
const showMobileMenu = ref(false);
</script>

<template>
  <div class="z-30 fixed top-0 w-full bg-primary text-white">
    <div
      class="relative h-[100px] pt-5 pr-4 w-full max-w-7xl flex justify-between items-center mx-auto"
    >
      <div
        v-if="showMobileMenu"
        id="mobileMenu"
        class="text-white absolute top-[100px] left-0 w-full h-[150px] bg-primary bg-opacity-[0.95] z-50"
      >
        <div class="flex flex-col items-center">
          <a class="w-full text-center" href="#">ГОЛОВНА</a>
          <a class="w-full text-center" href="#">КОНТАКТИ</a>
          <a class="w-full text-center" href="#">ПРО МЕНЕ</a>
        </div>
      </div>
      <div
        @click="showMobileMenu = !showMobileMenu"
        class="block md:hidden p-3"
      >
        <Hamburger />
      </div>
      <div>
        <img class="hidden md:block" src="/logo.png" width="80" alt="" />
      </div>
      <div class="md:flex gap-x-[60px] hidden">
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
