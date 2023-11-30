<script setup>
import Header from "@/components/Header.vue";
</script>

<template>
  <Header />
  <!-- Hero Section -->
  <div class="bg-primary">
    <div id="hero" class="h-[760px] relative bg-primary mt-[100px]">
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
    <div class="pt-[350px] flex justify-center relative bg-primary">
      <div class="absolute right-0 top-0 bg-primary">
        <img class="mix-blend-screen" src="/hero_bottom.png" alt="" />
      </div>
      <div class="">
        <ul class="text-[#E0E0E0] list-disc">
          <li>СПОРТИВНИЙ БЛОГ В Tiktok ТА instagram</li>
          <li>БЛИЗЬКО 6 РОКIВ У СПОРТI</li>
          <li>КВАЛIФIКАЦIЯ ТРЕНЕРА ТА ДIЄТОЛОГА</li>
          <li>Десятки гарних вIдгукIв та результатів</li>
        </ul>
      </div>
    </div>

    <!-- benifits -->
    <div class="text-4xl bg-primary pt-28">
      <div class="mb-9 text-white font-medium text-center">
        ВПЛИВ
        <span class="text-[#E5C140]">ТРЕНУВАНЬ</span>
        <br />
        ТА ЗДОРОВОГО ХАРЧУВАННЯ НА ЖИТТЯ ЛЮДИНИ
      </div>
      <div class="pt-40 mx-auto max-w-7xl">
        <div id="benifits" class="flex justify-center gap-x-9">
          <div class="benifit">
            <div class="relative h-[50%] w-full mb-4">
              <img src="/benifit_1.png" alt="" />
            </div>
            <div class="title">ГАРНА ФІЗИЧНА ФОРМА</div>
            <div class="desc">
              фізична активність і гарна форма сприяють кращому збереженню
              енергії, покращенню когнітивних функцій і підвищенню
              продуктивності у різних сферах життя.
            </div>
            <img
              class="mix-blend-difference"
              src="/logo.png"
              width="60"
              alt=""
            />
          </div>

          <div class="benifit">
            <div class="relative h-[50%] w-full mb-4">
              <img src="/benifit_2.png" alt="" />
            </div>
            <div class="title">РІВЕНЬ ЩАСТЯ</div>
            <div class="desc">
              Спорт підвищує рівень ендорфінів в організмі, що робить людину
              щасливішою, підвищує якість запам'ятовування, дозволяє більш
              структурно планувати та ефективно вирішувати проблеми.
            </div>
            <img
              class="mix-blend-difference"
              src="/logo.png"
              width="60"
              alt=""
            />
          </div>
          <div class="benifit">
            <div class="relative h-[50%] w-full mb-4">
              <img src="/benifit_3.png" alt="" />
            </div>
            <div class="title">ЗДОРОВЕ ХАРЧУВАННЯ</div>
            <div class="desc">
              Їжа дає енергію та будівельні матеріали кожній клітині нашого
              тіла. Якщо організм не отримує достатньої кількості корисних
              поживних речовин, обмінні процеси порушуються і страждає наше
              здоров'я.
            </div>
            <img
              class="mix-blend-difference"
              src="/logo.png"
              width="60"
              alt=""
            />
          </div>
        </div>
      </div>
    </div>

    <!-- pricing -->
    <div id="pricing" class="stripe-1 max-w-7xl mx-auto bg-primary pt-[240px]">
      <div class="mb-[70px] text-center text-white">
        <div class="font-medium text-[50px]">ТАРИФИ</div>
        <div class="font-medium text-[13px]">тривалість 1 місяць</div>
      </div>

      <div class="grid grid-flow-row grid-rows-3 gap-y-16">
        <div class="flex justify-center gap-x-11">
          <div class="pricing_card">
            <div class="heading">ТРЕНУВАННЯ ВДОМА</div>
            <div class="wrapper">
              <div class="price">350 ₴</div>
              <button>детальніше</button>
              <button class="yellow">придбати</button>
            </div>
          </div>
          <div class="pricing_card">
            <div class="heading">ТРЕНУВАННЯ В ЗАЛІ</div>
            <div class="wrapper">
              <div class="price">350 ₴</div>
              <button>детальніше</button>
              <button class="yellow">придбати</button>
            </div>
          </div>
        </div>
        <div class="flex justify-center gap-x-11">
          <div class="pricing_card">
            <div class="heading">ПЛАН ХАРЧУВАННЯ</div>
            <div class="wrapper">
              <div class="price">350 ₴</div>
              <button>детальніше</button>
              <button class="yellow">придбати</button>
            </div>
          </div>
          <div class="pricing_card">
            <div class="heading">ПЕРСОНАЛЬНЕ ВЕДЕННЯ</div>
            <div class="wrapper">
              <div class="price">350 ₴</div>
              <button>детальніше</button>
              <button class="yellow">придбати</button>
            </div>
          </div>
        </div>
        <div
          class="mx-auto w-[395px] h-[363px] text-center rounded-[44px] bg-[#E5C140] p-6"
        >
          <div class="mb-2 text-xl font-medium">ПЕРШЕ ТРЕНУВАННЯ</div>
          <div class="mb-6 text-[40px] font-medium">БЕЗКОШТОВНЕ</div>
          <input
            class="mb-3 w-full bg-[#24262A4D] rounded-full h-10"
            type="text"
          />
          <input
            class="mb-8 w-full bg-[#24262A4D] rounded-full h-10"
            type="text"
          />
          <button class="w-full h-14 text-white bg-[#24262A] rounded-full">
            СПРОБУВАТИ
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="postcss" scoped>
/* #hero {
  background-image: url("/hero_bg.png");
  background-size: fit;
  background-repeat: no-repeat;
  background-position: center;
} */
#benifits {
  .benifit {
    @apply h-[380px] w-1/3 px-6 relative rounded-[44px] bg-white flex flex-col items-center;

    img {
      @apply absolute bottom-0 left-0 right-0 mx-auto;
    }
    .title {
      @apply text-[#18191C] mb-2 text-xl  font-bold;
    }
    .desc {
      @apply text-[#18191C] text-sm;
    }
  }
}
.pricing_card {
  @apply w-[395px] h-[363px] rounded-[44px] bg-[#24262A] p-6;
  @apply flex flex-col justify-between items-center;
  > .heading {
    @apply text-white text-xl font-medium;
  }
  .wrapper {
    @apply w-full;
    .price {
      @apply text-[50px] font-semibold text-white text-center mb-4;
    }
    > button {
      @apply w-full h-14 text-white border rounded-full border-[#E5C140];
      @apply flex justify-center items-center;
    }
    > .yellow {
      @apply mt-3 text-black bg-[#E5C140];
    }
  }
}
.stripe-1 {
  background: linear-gradient(
    20deg,
    #18191c 35%,
    #ffffff 35%,
    #ffffff 65%,
    #18191c 50%
  );
}
</style>
