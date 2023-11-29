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
      class="z-10 absolute mx-auto right-0 left-0 top-[650px] text-4xl flex justify-center gap-x-4 text-white"
    >
      <button
        class="h-14 w-56 text-sm text-black font-medium rounded-full bg-[#E5C140]"
      >
        ПОЧАТИ
      </button>
      <button class="h-14 w-56 text-sm font-medium rounded-full border">
        ДЕТАЛЬНIШЕ
      </button>
    </div>
    dsa
  </div>
  <div>
    <img src="" alt="" />
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
