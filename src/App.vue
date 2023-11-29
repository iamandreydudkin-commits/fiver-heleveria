<script setup>
import Header from "@/components/Header.vue";
</script>

<template>
  <Header />
  <div id="hero" class="h-screen relative bg-primary mt-[100px]">
    <img
      class="z-[2] absolute mx-auto -top-6 right-0 left-3"
      src="/hero.png"
      alt=""
    />
    <img
      class="z-[1] absolute mx-auto right-0 left-0"
      src="/hero_bg.png"
      alt=""
    />
    <div
      class="z-10 absolute mx-auto right-0 left-0 top-[650px] text-4xl flex justify-center text-white"
    >
      <button></button>
      <button></button>
    </div>
    dsa
  </div>
</template>

<style lang="postcss" scoped>
/* #hero {
  background-image: url("/hero_bg.png");
  background-size: fit;
  background-repeat: no-repeat;
  background-position: center;
} */
</style>
