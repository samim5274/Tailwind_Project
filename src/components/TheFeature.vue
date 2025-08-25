<template>
  <div id="feature-line" class="container">
    <div class="border rounded-lg overflow-hidden flex justify-center p-4">      
      <div id="line4" class="flex gap-8 p-6">
          <h3 class="text-nowrap my-0 mx-2 text-lg font-semibold">Download Text</h3>
          <span>•</span>
          <h3 class="text-nowrap my-0 mx-2 text-lg font-semibold">Download Analysis</h3>
          <span>•</span>
          <h3 class="text-nowrap my-0 mx-2 text-lg font-semibold">Move Text</h3>
          <span>•</span>
          <h3 class="text-nowrap my-0 mx-2 text-lg font-semibold">Bar Text</h3>
          <span>•</span>
          <h3 class="text-nowrap my-0 mx-2 text-lg font-semibold">Hexiasol Text</h3>
          <span>•</span>
          <h3 class="text-nowrap my-0 mx-2 text-lg font-semibold">Neurosergon Text</h3>
          <span>•</span>
          <h3 class="text-nowrap my-0 mx-2 text-lg font-semibold">Merfozone Text</h3>
          <span>•</span>
          <h3 class="text-nowrap my-0 mx-2 text-lg font-semibold">Download Text</h3>
          <span>•</span>
          <h3 class="text-nowrap my-0 mx-2 text-lg font-semibold">Download Analysis</h3>
          <span>•</span>
          <h3 class="text-nowrap my-0 mx-2 text-lg font-semibold">Move Text</h3>
          <span>•</span>
          <h3 class="text-nowrap my-0 mx-2 text-lg font-semibold">Bar Text</h3>
          <span>•</span>
          <h3 class="text-nowrap my-0 mx-2 text-lg font-semibold">Hexiasol Text</h3>
          <span>•</span>
          <h3 class="text-nowrap my-0 mx-2 text-lg font-semibold">Neurosergon Text</h3>
          <span>•</span>
          <h3 class="text-nowrap my-0 mx-2 text-lg font-semibold">Merfozone Text</h3>
          <span>•</span>
      </div>
    </div>
  </div>
</template>

<script setup>
import { onMounted, onBeforeUnmount } from "vue";

const initialTranslateLTR = -48 * 4;
const initialTranslateRTL = 38 * 4;

function setupIntersectionObserver(element, isLTR, speed) {
  const scrollHandler = () => {
    const rect = element.getBoundingClientRect();
    const translateX = (window.innerHeight - rect.top) * speed;

    let totalTranslate = 0;
    if (isLTR) {
      totalTranslate = translateX + initialTranslateLTR;
    } else {
      totalTranslate = -(translateX + initialTranslateRTL);
    }

    element.style.transform = `translateX(${totalTranslate}px)`;
  };

  const intersectionCallback = (entries) => {
    const isIntersecting = entries[0].isIntersecting;
    if (isIntersecting) {
      document.addEventListener("scroll", scrollHandler);
    } else {
      document.removeEventListener("scroll", scrollHandler);
    }
  };

  const observer = new IntersectionObserver(intersectionCallback, {
    threshold: 0.15,
  });

  observer.observe(element);
}

onMounted(() => {
  const line4 = document.getElementById("line4");

  if (line4) setupIntersectionObserver(line4, false, 0.8);
});

</script>


<style>

</style>