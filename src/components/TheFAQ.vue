<template>
  <div class="container">
    <h2 class="text-5xl leading-normal sm:font-semibold max-w-2xl">FAQs</h2>
    <div class="grid grid-cols-1 lg:grid-cols-2 mt-6 gap-6 items-start">
      
      <div class="group rounded-xl border border-gray-200 bg-gray-50 p-6">
        <dt class="flex justify-between cursor-pointer" aria-controls="faq-1">
          <p class="font-semibold text-lg">Is ToDeskto For Me?</p>
          <i class="fa-solid fa-angle-up transition-transform duration-300 rotate-180"></i>
        </dt>
        <dd id="faq-1" class="hidden text-lg font-light mt-6">
          <p>
            That depends! If you would like to distribute your web app to your users 
            as a downloadable desktop app then ToDesktop is for you. If you want to 
            make a desktop app of a website for your personal use, ToDesktop is overkill.
          </p>
        </dd>
      </div>

      <div class="group rounded-xl border border-gray-200 bg-gray-50 p-6">
        <dt class="flex justify-between cursor-pointer" aria-controls="faq-2">
          <p class="font-semibold text-lg">Is ToDeskto For Me?</p>
          <i class="fa-solid fa-angle-up transition-transform duration-300 rotate-180"></i>
        </dt>
        <dd id="faq-2" class="hidden text-lg font-light mt-6">
          <p>
            That depends! If you would like to distribute your web app to your users 
            as a downloadable desktop app then ToDesktop is for you. If you want to 
            make a desktop app of a website for your personal use, ToDesktop is overkill.
          </p>
        </dd>
      </div>

      <div class="group rounded-xl border border-gray-200 bg-gray-50 p-6">
        <dt class="flex justify-between cursor-pointer" aria-controls="faq-3">
          <p class="font-semibold text-lg">Is ToDeskto For Me?</p>
          <i class="fa-solid fa-angle-up transition-transform duration-300 rotate-180"></i>
        </dt>
        <dd id="faq-3" class="hidden text-lg font-light mt-6">
          <p>
            That depends! If you would like to distribute your web app to your users 
            as a downloadable desktop app then ToDesktop is for you. If you want to 
            make a desktop app of a website for your personal use, ToDesktop is overkill.
          </p>
        </dd>
      </div>

      <div class="group rounded-xl border border-gray-200 bg-gray-50 p-6">
        <dt class="flex justify-between cursor-pointer" aria-controls="faq-4">
          <p class="font-semibold text-lg">Is ToDeskto For Me?</p>
          <i class="fa-solid fa-angle-up transition-transform duration-300 rotate-180"></i>
        </dt>
        <dd id="faq-4" class="hidden text-lg font-light mt-6">
          <p>
            That depends! If you would like to distribute your web app to your users 
            as a downloadable desktop app then ToDesktop is for you. If you want to 
            make a desktop app of a website for your personal use, ToDesktop is overkill.
          </p>
        </dd>
      </div>


    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    const dtElements = document.querySelectorAll("dt");

    dtElements.forEach((element) => {
      element.addEventListener("click", () => {
        const ddId = element.getAttribute("aria-controls");
        const ddElement = document.getElementById(ddId);
        const icon = element.querySelector("i");

        ddElement.classList.toggle("hidden");
        icon.classList.toggle("rotate-180");
      });
    });
  },
};
</script>
