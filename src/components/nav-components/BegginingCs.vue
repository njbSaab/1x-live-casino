<template>
    <div class="flex flex-col gap-[20px] text-left">
      <InfoShortBlock
        :title="infoData.title"
        :image="infoData.image"
        :content="infoData.content"
      />
    </div>
  </template>
  
  <script setup>
  import { ref } from "vue";
  import InfoShortBlock from "../layout/InfoShortBlock.vue"
  import image from "../../assets/img/main-n/beggining.png";

  
  const infoData = ref({
    title: "Начните свой опыт игры в казино на 1xBet    ",    
    content: `Начало вашего игрового путешествия в 1xBet Casino простое, что гарантирует вам быстрый переход к самой интересной части — игре в любимые игры казино. От регистрации до верификации и, наконец, наслаждения множеством предлагаемых нами игр, мы оптимизировали процесс, чтобы сделать его максимально гладким и беспроблемным.    `,
    image: image, 
  });

  
  </script>
  
  <style lang="scss" scoped></style>
  