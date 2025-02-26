<template>
    <div class="flex flex-col gap-[20px] text-left">
      <InfoShortBlock
        :title="infoData.title"
        :image="infoData.image"
        :content="infoData.content"
      />
    </div>
    <span class="line-bottom"></span>
  </template>
  
  <script setup>
  import { ref } from "vue";
  import InfoShortBlock from "../layout/InfoShortBlock.vue"
  import bingoImg from "../../assets/img/main-n/terms.svg";

  
  const infoData = ref({
    title: "Платежи в казино 1xBet",    
    content: `Навигация по платежным процессам в 1xBet Casino разработана так, чтобы быть простой и безопасной, гарантируя, что вы можете сосредоточиться на наслаждении игровым опытом без каких-либо хлопот. От внесения первого депозита до вывода выигрыша, мы гарантируем, что каждый шаг будет удобным для пользователя`,
    image: bingoImg, 
  });

  
  </script>
  
  <style lang="scss" scoped></style>
  