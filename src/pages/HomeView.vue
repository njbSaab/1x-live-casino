<template>
  <!-- banner -->
  <div class="banner">
    <BannerMain />
  </div>
  <!-- nav -->
  <div class="nav bg-main px-[18px] py-[45px] relative">
    <NavApp />
  </div>
  <div class="bg">
  <div class="container relative mt-[20px]">
    <!-- reg -->
    <div class="px-[18px] py-[20px]">
      <RegComponent />
    </div>
    <div class="reg-under-text px-[18px]">
      <RegUnderInfo />
    </div>
    <!-- how-to-start -->
    <div id="how-to" class="access-to px-[19px] py-[20px] relative">
      <HowToStart />
    </div>

    <!-- list game -->
    <div id="1xbet-casino" class="variety-of-sports px-[19px] py-[20px] relative">
      <VarietyOfGames />
    </div>

    <div id="casino-game" class="advantages px-[19px] py-[20px] relative">
      <AdvantagesOfChoosing />
    </div>

    <!-- top slots-->
    <div id="top-slot" class="ea-betting px-[19px] py-[20px] relative">
      <TopSlots />
    </div>

    <!-- live deallers-->
    <div id="live-dealer" class="bonus-betting px-[19px] py-[20px] relative">
      <LiveDeallers />
    </div>

    <!-- virtual -->
    <div id="1xbet-virtual" class="dep-list px-[19px] py-[20px] relative">
      <VirttualCasinoList />
    </div>

    <!-- instant-betting cas-->
    <div id="instant-betting" class="virt-casino px-[19px] py-[20px] relative">
      <InstanBetting />
    </div>

    <!-- 1xbet-unique -->
    <div id="1xbet-unique" class="dep-list px-[19px] py-[20px] relative">
      <UniqGamesList />
    </div>

    <!-- bingo -->
    <div id="1xbet-jackpot" class="experience-bingo px-[19px] md:pt-[10px] md:pb-[20px] relative">
      <ExperienceBingo />
    </div>

    <div id="tips-and" class="tips-list px-[19px] py-[20px]">
      <TipStrategyList />
    </div>

    <!-- reg -->
    <div class="px-[19px] py-[20px]">
      <RegComponent />
    </div>

    <div id="casino-bonuses" class="experience-bingo px-[19px] py-[20px] relative">
      <BonusServices />
    </div>

    <div id="casino-tournaments" class="deal-with px-[19px] py-[20px] relative">
      <DealWith />
    </div>

    <div id="ensuring-user" class="experience-bingo px-[19px] py-[20px] relative">
      <UserSufytty />
    </div>

    <div id="1xbet-responsible" class="responsible xbet-responsible px-[19px] py-[20px] relative">
      <ResponsibleApp />
    </div>

    <div id="which-currency" class="responsible px-[19px] pb-[20px] relative">
      <WhichCurrency />
    </div>

    <div id="responsible" class="responsible px-[19px] relative">
      <DepTerms />
    </div>

    <div id="using-crypto" class="responsible using-crypto relative">
      <UsingCrypto />
    </div>

    <div id="beginning-your" class="beginning-your relative">
      <BegginingCs />
    </div>
    <br />
    <!-- reg -->
    <div  id="conclusion" class="px-[19px] py-[20px]">
      <RegComponent />
      <FinalPart />
    </div>

  </div>
</div>
  <div id="faq" class="faq-info bg-main relative">
    <FaqInfo />
  </div>
</template>

<script setup>
import AdvantagesOfChoosing from "../components/nav-components/AdvantagesOfChoosing.vue";
import VarietyOfGames from "../components/nav-components/VarietyOfGames.vue";
import DealWith from "../components/nav-components/DealWith.vue";
import UniqGamesList from "../components/nav-components/UniqGamesList.vue";
import FaqInfo from "../components/nav-components/FaqInfo.vue";
import RegComponent from "../components/shared/RegComponent.vue";
import BannerMain from "../components/layout/BannerMain.vue";
import ExperienceBingo from "../components/nav-components/JackPotBlock.vue";
import NavApp from "../components/shared/NavApp.vue";
import RegUnderInfo from "../components/shared/RegUnderInfo.vue";
import HowToStart from "../components/nav-components/HowToStart.vue";
import TopSlots from "../components/nav-components/TopSlots.vue";
import LiveDeallers from "../components/nav-components/LiveDeallers.vue";
import VirttualCasinoList from "../components/nav-components/VirttualCasinoList.vue";
import InstanBetting from "../components/nav-components/InstanBetting.vue";
import BonusServices from "../components/nav-components/BonusServices.vue";
import UserSufytty from "../components/nav-components/UserSufytty.vue";
import ResponsibleApp from "../components/nav-components/ResponsibleApp.vue";
import WhichCurrency from "../components/nav-components/WhichCurrency.vue";
import DepTerms from "../components/nav-components/DepTerms.vue";
import UsingCrypto from "../components/nav-components/UsingCrypto.vue";
import BegginingCs from "../components/nav-components/BegginingCs.vue";
import FinalPart from "../components/shared/FinalPart.vue";
import TipStrategyList from "../components/nav-components/TipStrategyList.vue";
</script>

<style scoped>
/* Добавьте стили, если требуется */
</style>
