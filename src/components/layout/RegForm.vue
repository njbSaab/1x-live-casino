<!-- src/components/InfoBlock.vue -->
<template>
  <div
    class="info-reg flex flex-col gap-[20px] items-center text-center px-[18px] py-[24px]"
  >
    <div class="img-wrapper px-[20px]">
      <img :src="image" :alt="title" class="w-full object-cover" />
    </div>

    <div class="reg-body text-center w-full">
      <div
        class="title-group flex w-full justify-between items-center px-[5px] md:w-fit md:gap-[20px]"
      >
        <h2 class="text-2xl font-bold flex">{{ title }}</h2>
        <img class="" :src="titleIcon" alt="" />
      </div>
      <p class="text-white px-[20px]">{{ content }}</p>
    </div>
    <div class="btn-group flex flex-col gap-[20px] md:gap-[13px]">
      <button class="btn-main">
        {{ btnText }}
      </button>

      <a :href="btnLink" class="link-reg">{{ linkText }}</a>

      <span class="used text-black font-bold">{{ usedText }}</span>
    </div>
  </div>
</template>

<script setup>
import { defineProps } from "vue";

const props = defineProps({
  title: { type: String, required: true },
  image: { type: String, required: true },
  titleIcon: { type: String, required: true },
  content: { type: String, required: true },
  btnLink: { type: String, required: true },
  btnText: { type: String, required: true },
  linkText: { type: String, required: true },
  usedText: { type: String, required: true },
});
</script>

<style scoped lang="scss">
.info-reg {
  background: rgba(255, 255, 255, 0.2);
  background-size: cover;
  background-repeat: no-repeat;
  border-radius: 12px;
  .img-wrapper {
    width: 100%;
    background: #3c454a;
    backdrop-filter: blur(3px);
    border-radius: 12px;
    display: flex;
    align-items: center;
    padding: 40px 0;
    img {
      max-width: 200px;
      display: flex;
      align-items: center;
      margin: 0 auto;
      border-radius: 0;
    }
  }
  .reg-body {
    display: flex;
    flex-direction: column;
    gap: 20px;
    .title-group {
      h2 {
        font-size: 4.1vw;
        font-weight: 700;
        color: #ffffff;
        line-height: 1.5;
        text-align: left;
      }
    }
    .main-btn {
      max-width: 380px;
      margin: 0 auto;
    }
    .used {
      font-size: 3.5vw;
      line-height: 1.3;
      color: #000000;
      opacity: 0.8;
      font-weight: bold;
    }
    p {
      font-size: 16px;
      font-weight: 500;
      width: 100%;
      max-width: 350px;
      margin: 0 auto;
    }
  }
}
@media (min-width: 501px) {
  .info-reg {
    background-image: url(../../assets/img/desk/reg-bg-1.svg);
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    .reg-body {
      gap: 13px;
    }
    h2 {
      font-size: 30px;
    }
    p {
      font-size: 22px;
    }
    .img-wrapper {
      max-width: 250px;
      width: 100%;
    }
    .reg-body {
      flex: 1;
      text-align: start;
      p {
        max-width: 100%;
        padding: 0;
        font-size: 22px;
      }
    }
    .btn-group {
    }
  }
}
/* Стили для компонента InfoBlock */
</style>
