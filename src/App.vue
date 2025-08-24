<template>
  <TheMenu></TheMenu>
  <TheHeader></TheHeader>
  <TheSlide></TheSlide>
  <TheWork></TheWork>
  <TheCard></TheCard>
  <TheFeature></TheFeature>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import TheMenu from './components/TheMenu.vue';
import TheSlide from './components/TheSlide.vue';
import TheWork from './components/TheWork.vue';
import TheCard from './components/TheGrid.vue';
import TheFeature from './components/TheFeature.vue';

export default{
  components: {
    TheHeader,
    TheMenu,
    TheSlide,
    TheWork,
    TheCard,
    TheFeature,
  }
}
</script>

<style scoped>
/* https://www.youtube.com/watch?v=mGN9-FPsX9o&list=PLUcsbZa0qzu0OrMJWIuhvibOPZm_IHGTl 2:17:15 ses */
</style>
