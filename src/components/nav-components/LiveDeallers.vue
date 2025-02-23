<template>
  <div class="flex flex-col gap-[20px] text-left">
    <InfoShortBlock
      :title="bonus1.title"
      :image="bonus1.image"
      :content="bonus1.content"
    />
    <span class="line-bottom"></span>
    <InfoShortBlock
      :title="bonus2.title"
      :image="bonus2.image"
      :content="bonus2.content"
    />
    <span class="line-bottom"></span>
    <InfoShortBlock
      :title="bonus3.title"
      :image="bonus3.image"
      :content="bonus3.content"
    />
    <span class="line-bottom"></span>
    <InfoShortBlock
      :title="bonus4.title"
      :image="bonus4.image"
      :content="bonus4.content"
    />
    <span class="line-bottom"></span>
    <InfoShortBlock
      :title="bonus5.title"
      :image="bonus5.image"
      :content="bonus5.content"
    />
    <span class="line-bottom"></span>
    <InfoShortBlock
      :title="bonus6.title"
      :image="bonus6.image"
      :content="bonus6.content"
    />
    <span class="line-bottom"></span>
  </div>
</template>

<script setup>
import { ref } from "vue";
import InfoShortBlock from "../layout/InfoShortBlock.vue";
import image from "../../assets/img/live-deals-n/1.png";
import image2 from "../../assets/img/live-deals-n/2.png";
import image3 from "../../assets/img/live-deals-n/3.png";
import image4 from "../../assets/img/live-deals-n/4.png";
import image5 from "../../assets/img/live-deals-n/5.png";
import image6 from "../../assets/img/live-deals-n/6.png";

const bonus1 = ref({
  image: image,
  title: "Игры с живым дилером на 1xBet",
  content: `В 1xBet мы поднимаем опыт онлайн-казино на новый уровень с нашим выбором игр с живыми дилерами, перенося подлинность и волнение настоящего казино прямо на ваш экран. Наш раздел с живыми дилерами предлагает разнообразные игры, организованные профессиональными дилерами, что гарантирует действительно захватывающий игровой опыт. От классических настольных игр до уникальных игр в стиле живого шоу, наше живое казино создано для удовлетворения любых предпочтений.`,
});
const bonus2 = ref({
  title: "Живая баккара",
  content: `Live Baccarat на 1xBet передает суть одной из самых престижных игр казино. Игроки могут наслаждаться интерактивным опытом игры в баккара в реальном времени с живыми дилерами. Благодаря нескольким углам обзора и расширенным возможностям ставок вы почувствуете напряжение и волнение каждой сделки.    `,
  image: image2,
});
const bonus3 = ref({
  title: "Живая рулетка",
  content: `Вечная привлекательность рулетки воплощается в жизнь в нашем предложении Live Roulette. Игроки могут наблюдать за вращением колеса в реальном времени, делать ставки на настоящем столе рулетки и взаимодействовать с нашими живыми дилерами для получения непревзойденного игрового опыта. С такими разновидностями, как европейская, американская и французская рулетка, найдется игра для каждого любителя рулетки.`,
  image: image3,
});
const bonus4 = ref({
  title: "Живой блэкджек",
  content: `Испытайте острые ощущения от Live Blackjack на 1xBet, где каждая сданная рука обещает сочетание стратегии и шанса. Наши столы для Live Blackjack предлагают множество вариантов для игроков всех уровней, включая реальных дилеров и возможность взаимодействия с ними и другими игроками для общего игрового опыта.`,
  image: image4,
});
const bonus5 = ref({
  title: "Живой покер в казино",
  content: `Для любителей покера наш Live Casino Poker приносит стратегию и азарт самой популярной в мире карточной игры у вас дома. Сразитесь с дилером и другими игроками в реальном времени, с различными доступными версиями покера, каждая из которых обещает захватывающий игровой опыт.`,
  image: image5,
});
const bonus6 = ref({
  title: "Игры с живым колесом",
  content: `Если вы хотите чего-то немного необычного, наши игры Live Wheel Games предлагают веселый и динамичный игровой опыт. Эти игры, вдохновленные популярными телевизионными игровыми шоу, проводятся ведущими в прямом эфире и предлагают уникальное сочетание удачи и азарта, с возможностью выиграть по-крупному при каждом вращении.
  
В 1xBet наши игры с живым дилером выделяются своим разнообразием, качеством и захватывающим опытом, который они обеспечивают. Присоединяйтесь к нам, чтобы открыть для себя волнение от игры в живом казино и насладиться азартом казино, не выходя из дома.
`,

  image: image6,
});
</script>

<style lang="scss" scoped></style>
