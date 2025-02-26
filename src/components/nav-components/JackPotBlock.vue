<template>
    <div class="flex flex-col gap-[20px] pb-[20px] text-left">
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
  import image from "../../assets/img/main-n/jackpot.png"

  
  const infoData = ref({
    title: "1xBet Джекпот",
    content: `В 1xBet азарт игры достигает своего пика с нашими предложениями джекпота. Мы предоставляем нашим игрокам волнующую возможность выиграть по-крупному с помощью различных игр с джекпотом. Каждая игра разработана так, чтобы предложить не только веселье и азарт, но и шанс выиграть суммы, которые изменят жизнь. Будь то вращение барабанов на наших слотах или ставки на спорт, мечта сорвать джекпот всегда в пределах досягаемости. Наши джекпоты прогрессивные, то есть они растут с каждой сделанной ставкой, пока один счастливчик не заберет все. Это добавляет дополнительный уровень волнения к вашему игровому опыту, зная, что любой момент может превратиться в монументальную победу. Присоединяйтесь к нам в 1xBet и пусть начнется погоня за джекпотом.    `,
    image: image, 
  });

  
  </script>
  
  <style lang="scss" scoped></style>
  