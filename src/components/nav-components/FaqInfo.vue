<template>
  <div class="faq-info pt-[33px] pb-[63px] px-[20px] text-left">
    <h2 class="text-2xl mx-auto w-fit text-white font-bold pb-[25px] flex items-center gap-3">
      FAQ
    </h2>
    <div class="flex flex-col gap-[20px]">
      <FaqInfo :title="infoData1.title" :content="infoData1.content" />
      <FaqInfo :title="infoData2.title" :content="infoData2.content" />
      <FaqInfo :title="infoData3.title" :content="infoData3.content" />
      <FaqInfo :title="infoData4.title" :content="infoData4.content" />
      <FaqInfo :title="infoData5.title" :content="infoData5.content" />
      <FaqInfo :title="infoData6.title" :content="infoData6.content" />
      <FaqInfo :title="infoData6.title" :content="infoData7.content" />
    </div>
  </div>
</template>

<script setup>
import { ref } from "vue";
import FaqInfo from "../layout/FaqInfo.vue";

const infoData1 = ref({
  title: "Что такое онлайн-казино 1xBet?",
  content:
    "1xBet Online Casino — это комплексная онлайн-платформа для азартных игр, которая предлагает широкий выбор игр казино, включая слоты, настольные игры, игры с живым дилером и виртуальный спорт. Она обеспечивает безопасную и захватывающую игровую среду как для новичков, так и для опытных игроков.",
});
const infoData2 = ref({
  title: "Могу ли я играть в 1xBet Casino на своем мобильном устройстве?",
  content: `Да, 1xBet Casino предлагает мобильное приложение, совместимое с операционными системами Android, iOS и Windows, что позволяет игрокам наслаждаться любимыми играми казино на ходу.`,
});
const infoData3 = ref({
  title: "Какие способы оплаты доступны в казино 1xBet?",
  content: `Казино 1xBet поддерживает различные способы оплаты, включая кредитные/дебетовые карты, электронные кошельки, банковские переводы, предоплаченные карты и широкий спектр криптовалют, таких как Bitcoin, Ethereum и Litecoin.
`,
});
const infoData4 = ref({
  title: "Есть ли бонусы для новых игроков в казино 1xBet?",
  content: `Новые игроки в казино 1xBet могут выбрать приветственный бонус на спорт или слоты, который включает бонусы за матч и бесплатные вращения на их первоначальные депозиты при условии соблюдения требований по отыгрышу.
`,
});const infoData5 = ref({
  title: "Как зарегистрироваться в казино 1xBet?",
  content: `Регистрация в 1xBet Casino проста. Игроки могут зарегистрироваться в один клик, по телефону, электронной почте или через социальные сети/медиа, заполнив необходимую информацию и согласившись с условиями.

`,
});
const infoData6 = ref({
  title: "Безопасно ли и честно ли казино 1xBet?",
  content: `Казино 1xBet использует самые современные технологии шифрования для защиты данных пользователей и гарантирует честную игру с помощью регулярно проверяемых генераторов случайных чисел (ГСЧ).
`,
});
const infoData7 = ref({
  title: "Как я могу вывести свой выигрыш из казино 1xBet?",
  content: `Вывод средств в 1xBet Casino осуществляется тем же методом, что и для депозитов. Сроки вывода средств зависят от метода, при этом электронные кошельки обычно предлагают самые быстрые выплаты.`,
});
</script>

<style lang="scss" scoped></style>
