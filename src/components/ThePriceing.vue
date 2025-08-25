<template>
  <div class="container">
    <h2 class="text-4xl leading-normal lg:text-6xl sm:font-semibold max-w-2xl">
      Choose a plan that fits your needs
    </h2>

    <!-- flex row with equal height cards -->
    <div class="flex flex-col lg:flex-row gap-4 mt-4 items-stretch">
      <!-- Card 1 -->
      <div class="border lg:border-none lg:bg-slate-100 rounded-lg px-8 py-12 pb-8 mt-4 grid gap-4 h-full flex-1">
        <h3 class="text-4xl">Free</h3>
        <p class="text-lg font-light">
          For personal use or testing your app before deploying to customers.
        </p>

        <div class="uppercase">key features</div>

        <ul class="space-y-3 mt-4">
          <li class="flex items-center gap-4">
            <i class="fa-solid fa-check text-green-400"></i>
            <span class="text-lg font-light text-gray-800">Free for Personal Use</span>
          </li>
          <li class="flex items-center gap-4">
            <i class="fa-solid fa-check text-green-400"></i>
            <span class="text-lg font-light text-gray-800">Run App Locally</span>
          </li>
          <li class="flex items-center gap-4">
            <i class="fa-solid fa-check text-green-400"></i>
            <span class="text-lg font-light text-gray-800">Real IPv4/IPv6</span>
          </li>
          <li class="flex items-center gap-4">
            <i class="fa-solid fa-xmark text-red-400"></i>
            <span class="text-lg font-light text-gray-800">No Public Distribution</span>
          </li>
          <li class="flex items-center gap-4">
            <i class="fa-solid fa-xmark text-red-400"></i>
            <span class="text-lg font-light text-gray-800">No Native Installers</span>
          </li>
        </ul>

        <button
          class="border w-full px-8 py-3 mt-auto text-blue-600 rounded-lg hover:border-gray-800 font-display font-medium"
        >
          Read Docs
        </button>
      </div>

      <!-- Card 2 -->
      <div class="border lg:border-none lg:bg-slate-100 rounded-lg px-8 py-12 pb-8 mt-4 grid gap-4 h-full flex-1">
        <h3 class="text-4xl">Essential</h3>
        <p class="text-lg font-light">For simple desktop apps.</p>

        <p class="text-lg font-light">
          <span class="text-2xl font-semibold">$99</span>/month
        </p>

        <div class="uppercase">key features</div>

        <ul class="space-y-3 mt-4">
          <li class="flex items-center gap-4">
            <i class="fa-solid fa-check text-green-400"></i>
            <span class="text-lg font-light text-gray-800">Free for Personal Use</span>
          </li>
          <li class="flex items-center gap-4">
            <i class="fa-solid fa-check text-green-400"></i>
            <span class="text-lg font-light text-gray-800">Run App Locally</span>
          </li>
          <li class="flex items-center gap-4">
            <i class="fa-solid fa-check text-green-400"></i>
            <span class="text-lg font-light text-gray-800">Real IPv4/IPv6</span>
          </li>
          <li class="flex items-center gap-4">
            <i class="fa-solid fa-xmark text-red-400"></i>
            <span class="text-lg font-light text-gray-800">No Public Distribution</span>
          </li>
          <li class="flex items-center gap-4">
            <i class="fa-solid fa-xmark text-red-400"></i>
            <span class="text-lg font-light text-gray-800">No Native Installers</span>
          </li>
        </ul>

        <button
          class="border w-full px-8 py-3 mt-auto text-blue-600 rounded-lg hover:border-gray-800 font-display font-medium"
        >
          Read Docs
        </button>
      </div>

      <!-- Card 3 -->
      <div class="border lg:border-none lg:bg-slate-100 rounded-lg px-8 py-12 pb-8 mt-4 relative grid gap-4 h-full flex-1">
        <p
          class="text-blue-800 text-sm bg-indigo-100 rounded-full w-fit px-4 py-2 font-display absolute top-0 right-8 -translate-y-1/2 font-semibold"
        >
          Most popular
        </p>

        <h3 class="text-4xl">Professional</h3>
        <p class="text-lg font-light">For sophisticated desktop apps.</p>

        <p class="text-lg font-light">
          <span class="text-2xl font-semibold">$99</span>/month
        </p>

        <div class="uppercase">key features</div>

        <ul class="space-y-3 mt-4">
          <li class="flex items-center gap-4">
            <i class="fa-solid fa-check text-green-400"></i>
            <span class="text-lg font-light text-gray-800">Free for Personal Use</span>
          </li>
          <li class="flex items-center gap-4">
            <i class="fa-solid fa-check text-green-400"></i>
            <span class="text-lg font-light text-gray-800">Run App Locally</span>
          </li>
          <li class="flex items-center gap-4">
            <i class="fa-solid fa-check text-green-400"></i>
            <span class="text-lg font-light text-gray-800">Real IPv4/IPv6</span>
          </li>
          <li class="flex items-center gap-4">
            <i class="fa-solid fa-xmark text-red-400"></i>
            <span class="text-lg font-light text-gray-800">No Public Distribution</span>
          </li>
          <li class="flex items-center gap-4">
            <i class="fa-solid fa-xmark text-red-400"></i>
            <span class="text-lg font-light text-gray-800">No Native Installers</span>
          </li>
        </ul>

        <button
          class="w-full bg-blue-500 px-8 py-3 mt-auto text-white rounded-lg hover:bg-blue-400 font-display font-medium"
        >
          Read Docs
        </button>
      </div>
    </div>
  </div>
</template>


<script lang="ts" setup>

</script>

<style>

</style>