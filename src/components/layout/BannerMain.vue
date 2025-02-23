<template>
  <div
    class="banner-block flex flex-col items-center gap-[20px] bg-transparent px-[18px] py-[37px] text-start"
  >
  <div class="benner-content flex flex-col gap-[20px]">
    <h1 class="font-bold italic text-start mr-auto"
    :style="{ whiteSpace: 'pre-wrap' }"
    >{{ bannerData.title }}</h1>
    <p class="text-base">
      {{ bannerData.listDescription }}
    </p>
  </div>
    <div
      class="bonus-group bg-img w-full flex items-start"
    >
      <button class="btn-main-sm flex gap-2 items-center justify-center mt-auto">
        <svg
          width="23"
          height="21"
          viewBox="0 0 23 21"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M8.75 0.710216C6.86 0.700216 5.02 2.52022 5.86 4.78022H2.69C2.15957 4.78022 1.65086 4.99093 1.27579 5.366C0.900712 5.74108 0.690002 6.24978 0.690002 6.78022V8.7802C0.690002 9.0454 0.795362 9.2998 0.982892 9.4873C1.17043 9.6749 1.42478 9.7802 1.69 9.7802H10.69V6.78022H12.69V9.7802H21.69C21.9552 9.7802 22.2096 9.6749 22.3971 9.4873C22.5846 9.2998 22.69 9.0454 22.69 8.7802V6.78022C22.69 6.24978 22.4793 5.74108 22.1042 5.366C21.7291 4.99093 21.2204 4.78022 20.69 4.78022H17.52C18.69 1.51022 14.29 -0.799787 12.26 2.02022L11.69 2.78022L11.12 2.00022C10.49 1.11022 9.62 0.720216 8.75 0.710216ZM8.69 2.78022C9.58 2.78022 10.03 3.86022 9.4 4.49022C8.77 5.12022 7.69 4.67022 7.69 3.78022C7.69 3.515 7.79536 3.26065 7.98289 3.07311C8.17043 2.88557 8.42478 2.78022 8.69 2.78022ZM14.69 2.78022C15.58 2.78022 16.03 3.86022 15.4 4.49022C14.77 5.12022 13.69 4.67022 13.69 3.78022C13.69 3.515 13.7954 3.26065 13.9829 3.07311C14.1704 2.88557 14.4248 2.78022 14.69 2.78022ZM1.69 10.7802V18.7802C1.69 19.3107 1.90071 19.8194 2.27579 20.1944C2.65086 20.5695 3.15957 20.7802 3.69 20.7802H19.69C20.2204 20.7802 20.7291 20.5695 21.1042 20.1944C21.4793 19.8194 21.69 19.3107 21.69 18.7802V10.7802H12.69V18.7802H10.69V10.7802H1.69Z"
            fill="white"
          />
        </svg>
        {{ bannerData.btnText }}
      </button>
    </div>

  </div>
</template>

<script setup>
import { ref } from "vue";
import image from "../../assets/img/deposit.png";

const bannerData = ref({
  title: `Онлайн-казино 1xBet в Японии:\nслоты, живые и виртуальные игры`,
    listDescription: `Погрузитесь в непревзойденный игровой опыт с нашим всесторонним обзором 1xBet Online Casino, рассчитанным как на новичков, так и на опытных игроков. В этой статье рассматриваются все аспекты, от простой регистрации, разнообразного выбора игр и уникальных игр казино до безопасных вариантов оплаты, включая криптовалюты. Узнайте о нашем мобильном приложении, бонусах казино и ответственной игровой практике. Присоединяйтесь сейчас, чтобы получить 100% бонус на первый депозит до ________ йен и приветственный пакет до _____________ йен + 150 бесплатных вращений.`,
  btnLink: "https://google.com",
  image: image,
  btnText: "Подробнее",
});
</script>

<style scoped lang="scss">
.banner-block {
  background-image: url(../../assets/img/banner-n/back.svg);
  background-repeat: no-repeat;
  background-size: cover;

  .bonus-group{
    height: 208px;
  }
  .btn-main-sm{
    margin-top: auto;
    margin-left: 35px;
    margin-bottom: 5px;
  }

  .group-title {
    h2 {
      font-size: 30px;
      font-weight: bold;
      text-shadow: 0 4px 3px rgba(0, 0, 0, 0.492);
    }
    p {
      font-size: 16px;
      text-shadow: 0 4px 3px rgba(0, 0, 0, 0.492);
    }
  }

  .bg-img {
    backdrop-filter: blur(5px);
    border-radius: 12px;
    position: relative;
    overflow: hidden;
    &::before {
      position: absolute;
      content: "";
      width: 100%;
      height: 100%;
      left: 0;
      bottom: 0;
      background-image: url(../../assets/img/banner-n/picture-bonus.svg);
      background-repeat: no-repeat;
      background-size: cover;      
      z-index: 0;
    }
  }

  h1 {
    font-size: 14px;
    font-weight: 700;
    color: #ffffff;
    line-height: 1.5;
  }
  .btn-main {
    max-width: 280px;
    margin: 0 auto;
    width: 100%;
  }
  p {
    font-size: 14px;
    line-height: 1.3;
    color: #ffffff;
    opacity: 1;
  }
}

/* Стили для компонента InfoBlock */
</style>
