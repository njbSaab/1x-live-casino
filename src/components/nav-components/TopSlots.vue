<template>
  <div class="text-left flex flex-col gap-[20px]">
    <InfoShortBlock
      :title="infoData.title"
      :image="infoData.image"
      :content="infoData.content"
    />
    <span class="line-bottom"></span>
    <InfoShortBlock
      :title="infoData2.title"
      :image="infoData2.image"
      :content="infoData2.content"
    />
    <span class="line-bottom"></span>
    <InfoShortBlock
      :title="infolol.title"
      :image="infolol.image"
      :content="infolol.content"
    />
    <span class="line-bottom"></span>
    <InfoShortBlock
      :title="infoCs2.title"
      :image="infoCs2.image"
      :content="infoCs2.content"
    />
    <span class="line-bottom"></span>
    <InfoShortBlock
      :title="infoFifa.title"
      :image="infoFifa.image"
      :content="infoFifa.content"
    />
  </div>
</template>

<script setup>
import { ref } from "vue";
import InfoShortBlock from "../layout/InfoShortBlock.vue";
import image from "../../assets/img/top-slots-n/1.png";
import image2 from "../../assets/img/top-slots-n/2.png";
import image3 from "../../assets/img/top-slots-n/3.png";
import image4 from "../../assets/img/top-slots-n/4.png";
import image5 from "../../assets/img/top-slots-n/5.png";

const infoData = ref({
  title: "Лучшие слот-игры на 1xBet",
  content: `В 1xBet волнение казино оживает на вашем экране с нашими лучшими слот-играми. От блеска и гламура Голливуда до древних гробниц Египта, наш разнообразный ассортимент тематических слотов гарантирует, что каждый игрок найдет свой кусочек приключения. Благодаря играм от ведущих поставщиков, таких как EGT, NetEnt и Microgaming, наши слоты предлагают не только захватывающий игровой процесс, но и шанс выиграть по-крупному всего за одно вращение. Погрузитесь в наши самые популярные слоты и узнайте, почему 1xBet является выбором для любителей онлайн-слотов.
`,
  image: image,
});
const infoData2 = ref({
  title: "Горячая мания",
  content: `Почувствуйте жар с Hot Mania, слотом, который поднимает температуру на ступеньку выше с его огненными темами и такими же горячими джекпотами. Идеально подходит для игроков, которые любят высокие ставки и яркие визуальные эффекты, Hot Mania обещает волнующий опыт с каждым вращением.`,
  image: image2,
});
const infolol = ref({
  title: "Фортуна Пять",
  content: `Fortune Five предлагает уникальный поворот в традиционных слот-играх с инновационной механикой и увлекательными функциями, которые заставляют игроков возвращаться снова и снова. Его сочетание классического игрового процесса и современных бонусов делает его выдающимся выбором для тех, кто ищет свежий взгляд на игровой процесс.`,
  image: image3,
});
const infoCs2 = ref({
  title: "Пылающе горячо",
  content: `Подними жару с Blazing Hot, игрой-слотом, которая сочетает в себе горячие темы с шансом выиграть обжигающие призы. Ее классическая привлекательность слота в сочетании с современными функциями обеспечивает сбалансированный игровой опыт как для новичков, так и для опытных игроков.`,
  image: image4,
});
const infoFifa = ref({
  title: "Cash'n Fruits",
  content: `Сочные выигрыши ждут в Cash'n Fruits, где яркая графика и сладкие награды делают игровой процесс заманчивым. Эта игра идеально подходит для тех, кто любит более традиционные ощущения от игровых автоматов, с дополнительными волнениями от потенциальных крупных выигрышей с каждым вращением.
  
В 1xBet мы стремимся предоставлять прозрачный и честный игровой опыт. Наш выбор слотов, включающий все, от видео до 3D-опций, гарантирует, что каждый игрок сможет найти свою идеальную игру. Присоединяйтесь к нам и откройте для себя волнение онлайн-слотов в 1xBet, где один спин может превратиться в целое состояние.`,
  image: image5,
});
</script>

<style lang="scss" scoped></style>
