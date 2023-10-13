<template>
  <h2 class="h2">SISTEMA JOW GA KUNG FU</h2>
  <JowGaHistory />
  <YouWillLearn />
  <WayToFight />
  <OptimizingFocus/>
  <ValidatedSharpening/>
  <BaseOfEverything/>
  <WhyTrainJowGaVue/>
  <MeetYourInstructor/>
  <ThisIsForYou/>
  <IPreventYouFromRisks/>
  <CallToAction/>
</template>

<script>
import JowGaHistory from './JowGaHistory/JowGaHistory.vue';
import YouWillLearn from './YouWillLearn/YouWillLearn.vue';
import WayToFight from './WayToFight/WayToFight.vue'
import OptimizingFocus from './OptimizingFocus/OptimizingFocus.vue'
import ValidatedSharpening from './ValidatedSharpening/ValidatedSharpening.vue';
import BaseOfEverything from './BaseOfEverything/BaseOfEverything.vue';
import WhyTrainJowGaVue from './WhyTrainJowGa/WhyTrainJowGa.vue';
import MeetYourInstructor from './MeetYourInstructor/MeetYourInstructor.vue';
import ThisIsForYou from './ThisIsForYou/ThisIsForYou.vue';
import IPreventYouFromRisks from './IPreventYouFromRisks/IPreventYouFromRisks.vue';
import CallToAction from './CallToAction/CallToAction.vue';

export default {
  name: 'Home',

  components: {
    JowGaHistory,
    YouWillLearn,
    WayToFight,
    OptimizingFocus,
    ValidatedSharpening,
    BaseOfEverything,
    WhyTrainJowGaVue,
    MeetYourInstructor,
    ThisIsForYou,
    IPreventYouFromRisks,
    CallToAction
  }
}
</script>

<style scoped>
.h2 {
  padding-top: 150px;
  text-align: center;
  color: gold;
  font-size: 40px;
  animation: fallAnimation 1s ease-out;
}

@keyframes fallAnimation {
  0% {
    opacity: 0;
    transform: translateX(+100%);
  }

  100% {
    opacity: 1;
    transform: translateX(0);
  }
}
</style>