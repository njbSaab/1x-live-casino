<!-- src/components/InfoBlock.vue -->
<template>
  <div class="info-block flex flex-col gap-[20px] text-left">
    <h2 v-if="title" class="text-2xl font-bold">{{ title }}</h2>
    <img
      v-if="image"
      :src="image"
      :alt="title"
      class="w-full object-cover rounded-[10px]"
    />
    <p v-if="content" class="text-base text-content">{{ content }}</p>
  </div>
</template>

<script setup>
import { defineProps } from "vue";

const props = defineProps({
  title: { type: String, required: false },
  image: { type: String, required: false },
  content: { type: String, required: false },
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

/* Стили для компонента InfoBlock */
</style>
