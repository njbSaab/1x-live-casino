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
import image from "../../assets/img/bonus-n/1.png";
import image2 from "../../assets/img/bonus-n/2.png";
import image3 from "../../assets/img/bonus-n/3.png";
import image4 from "../../assets/img/bonus-n/4.png";
import image5 from "../../assets/img/bonus-n/5.png";
import image6 from "../../assets/img/desk/earning.png";

const bonus1 = ref({
  image: image,
  title: "Бонусы казино 1xBet",
  content: `В 1xBet мы делаем все возможное, чтобы вознаградить как новых, так и постоянных игроков одними из самых конкурентоспособных бонусов в мире онлайн-казино. С того момента, как вы присоединитесь к нам, вас ждет множество бонусов, которые улучшат ваш игровой опыт, предоставив вам больше шансов на победу и гарантируя максимальное удовольствие. Вот более подробный обзор разнообразных бонусов, которые вы можете ожидать в казино 1xBet.`,
});
const bonus2 = ref({
  title: "Получение бесплатных вращений",
  content: `Бесплатные вращения являются ключевой частью нашего приветственного предложения слотов, предоставляя вам возможность испытать наши разнообразные слоты без необходимости сразу же делать ставки на собственные деньги. Они доступны в течение ваших первых четырех депозитов, гарантируя теплый прием в нашем казино.`,
  image: image2,
});
const bonus3 = ref({
  title: "Получение приветственного бонуса 1xBet",
  content: `Выбирая между спортивными состязаниями или слотами, наш приветственный бонус удовлетворяет ваши предпочтения с самого начала. Для любителей слотов до 620000 JPY плюс 150 бесплатных вращений могут стать вашими с вашим первым депозитом, гарантируя захватывающее начало вашего путешествия 1xBet.`,
  image: image3,
});
const bonus4 = ref({
  title: "Получение реферального бонуса",
  content: `Распространите информацию о 1xBet среди друзей и получите бонусы в знак нашей признательности. Это наш способ сказать спасибо за помощь в развитии нашего сообщества.`,
  image: image4,
});
const bonus5 = ref({
  title: "Получение бонуса на депозит",
  content: `Наши бонусы на депозиты разработаны так, чтобы соответствовать проценту вашего депозита с бонусными средствами. С возможностью получить до четырех, начиная с 100% бонуса плюс бесплатные вращения на ваш первый депозит, награды просто продолжают поступать.`,
  image: image5,
});
const bonus6 = ref({
  title: "Получение кэшбэка",
  content: `Лояльность окупается нашей системой кэшбэка. Чем больше вы играете, тем больше вы можете получить взамен, гарантируя, что каждая ставка будет иметь значение, даже если удача не на вашей стороне.
  
Наши бонусы созданы для улучшения вашего игрового опыта, предоставляя вам дополнительные средства или бесплатные вращения, чтобы исследовать все, что может предложить 1xBet Casino. Окунитесь в действие сегодня и узнайте, как наши бонусы могут дать вам преимущество в вашем следующем игровом приключении.`,

  image: image6,
});
</script>

<style lang="scss" scoped></style>
