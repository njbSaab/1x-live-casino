<!-- src/components/InfoBlock.vue -->
<template>
  <div
    class="info-block flex flex-col gap-[20px] md:gap-[26px] bg-transparent text-left py-[20px] elipse"
  >
    <h2 v-if="title" class="text-2xl font-bold">{{ title }}</h2>
    <div class="wrapper flex flex-col md:gap[36px] gap-[25px] md:flex-row">
      <img
        v-if="image"
        :src="image"
        :alt="title"
        class="w-full object-cover rounded-[10px]"
      />

      <p v-if="content" class="text-base text-content md:w-[100%]">{{ content }}</p>
    </div>
    <p v-if="contentNext" class="text-base text-content w-full">
      {{ contentNext }}
    </p>
  </div>
</template>

<script setup>
import { defineProps } from "vue";

const props = defineProps({
  title: { type: String, required: false },
  image: { type: String, required: false },
  content: { type: String, required: false },
  contentNext: { type: String, required: false },
  imageDesktop: { type: String, required: false },
});
</script>

<style scoped lang="scss">
.info-block {
  h2 {
    font-size: 22px;
    font-weight: 700;
    color: #ffffff;
    line-height: 1.5;
  }
  p {
    font-size: 14px;
    line-height: 1.3;
    color: #ffffff;
    // text-shadow: 0 0 5px white;
    opacity: 0.9;
  }
}
@media (min-width: 501px) {
  .info-block {
    h2 {
      font-size: 28px;
      line-height: 1;
    }
    p {
      font-size: 16px;
    }
  }
  .desk {
    display: block;
  }
  .mob {
    display: none;
  }
  .info-block .wrapper{
    flex-direction: row-reverse;
    img{
      
    }
  }
}
/* Стили для компонента InfoBlock */
</style>
