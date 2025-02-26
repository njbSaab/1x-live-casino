<template>
    <div class="rounded-[10px] text-left">
      <InfoShortBlock
        :title="regData.title"
        :image="regData.image"
        :content="regData.content"
      />
    </div>
    <span class="line-bottom"></span>

  </template>
  
  <script setup>
  import { ref } from "vue";
  import InfoShortBlock from "../layout/InfoShortBlock.vue";
  import image from "../../assets/img/main-n/how-to.png";
  
  const regData = ref({
    title: "Как начать играть в казино 1xBet?",
    content: `Начало вашего игрового путешествия в 1xBet Online Casino простое и разработано для вашего максимального удобства. Наша платформа приветствует каждого энтузиаста, чтобы с легкостью окунуться в захватывающий мир онлайн-гемблинга. Вот как вы можете начать играть с нами, гарантируя плавный переход к азарту онлайн-игр казино.
  `,
    image: image, 
  });
  </script>
  
  <style lang="scss" scoped></style>
  