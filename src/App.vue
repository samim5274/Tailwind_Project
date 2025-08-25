<template>
  <TheMenu></TheMenu>
  <TheHeader></TheHeader>
  <TheSlide></TheSlide>
  <TheWork></TheWork>
  <TheCard></TheCard>
  <TheFeature></TheFeature>
  <TheTestimonial></TheTestimonial>
  <TheTestimonial2></TheTestimonial2>
  <TheBigCard></TheBigCard>
  <ThePrice></ThePrice>
  <TheFAQ></TheFAQ>
  <TheFooter></TheFooter>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import TheMenu from './components/TheMenu.vue';
import TheSlide from './components/TheSlide.vue';
import TheWork from './components/TheWork.vue';
import TheCard from './components/TheGrid.vue';
import TheFeature from './components/TheFeature.vue';
import TheTestimonial from './components/TheTestimonial.vue';
import TheTestimonial2 from './components/TheTestimonial-2.vue';
import TheBigCard from './components/TheBigCard.vue';
import ThePrice from './components/ThePriceing.vue';
import TheFAQ from './components/TheFAQ.vue';
import TheFooter from './components/TheFooter.vue';

export default{
  components: {
    TheHeader,
    TheMenu,
    TheSlide,
    TheWork,
    TheCard,
    TheFeature,
    TheTestimonial,
    TheTestimonial2,
    TheBigCard,
    ThePrice,
    TheFAQ,
    TheFooter,
  }
}
</script>

<style scoped>
/* https://www.youtube.com/watch?v=mGN9-FPsX9o&list=PLUcsbZa0qzu0OrMJWIuhvibOPZm_IHGTl 2:17:15 ses */
</style>
