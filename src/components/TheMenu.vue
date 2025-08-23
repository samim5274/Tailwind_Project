<template>
  <nav class="p-3 flex bg-white justify-between items-center">
    <a href="#" id="brand" class="flex gap-2 items-center flex-1">
      <img src="../../public/img/pngegg.png" alt="NARUTO" class="object-cover max-w-12 max-h-12">
      <span class="text-2xl font-medium">Supper Man</span>
    </a>

    <div id="nav-manu" class="hidden lg:flex gap-12">
      <a href="#" class="font-medium hover:text-blue-500">Pricing</a>
      <a href="#" class="font-medium hover:text-blue-500">Docs</a>
      <a href="#" class="font-medium hover:text-blue-500">Changelog</a>
      <a href="#" class="font-medium hover:text-blue-500">Blogs</a>
      <a href="#" class="font-medium hover:text-blue-500">Login</a>
    </div>

    <div class="hidden lg:flex flex-1 justify-end">
      <button class="flex gap-2 items-center border-1 border-gray-400 p-2 rounded-lg hover:border-gray-600 ">
        <i class="fa-solid fa-atom text-xl text-gray-400"></i>
        <span>Electron Devlopers</span> <span><i class="fa-solid fa-arrow-right"></i></span>
      </button>
    </div>

    <button class="p-2 lg:hidden" @click="handleMenu()"><i class="fa-solid fa-bars text-gray-600"></i></button>

    <div id="nav-menu" v-show="isOpen" class="fixed bg-white inset-0 p-3 z-10 lg:hidden">
      <div id="nav-bar" class="flex justify-between">
        <a href="#" id="brand" class="flex gap-2 items-center">
          <img src="../../public/img/pngegg.png" alt="NARUTO" class="object-cover max-w-12 max-h-12">
          <span class="text-2xl font-medium">Supper Man</span>
        </a>
        <button class="p-2 lg:hidden" @click="handleMenu()"><i class="fa-solid fa-xmark text-gray-600"></i></button>
      </div>
      <div class="mt-6">
        <a href="#" class="font-mediam m-3 p-3 hover:bg-gray-200 rounded-lg block">Pricing</a>
        <a href="#" class="font-mediam m-3 p-3 hover:bg-gray-200 rounded-lg block">Docs</a>
        <a href="#" class="font-mediam m-3 p-3 hover:bg-gray-200 rounded-lg block">Changelog</a>
        <a href="#" class="font-mediam m-3 p-3 hover:bg-gray-200 rounded-lg block">Blogs</a>
        <a href="#" class="font-mediam m-3 p-3 hover:bg-gray-200 rounded-lg block">Login</a>
      </div>
      <div class="h-[1px] bg-gray-300"></div>
        <button class="w-full mt-6 flex gap-2 items-center p-4 rounded-lg hover:bg-gray-100">
          <i class="fa-solid fa-atom text-xl text-gray-400"></i>
          <span>Electron Devlopers</span>
        </button>
    </div>
    
  </nav>
</template>

<script>
export default {
  data() {
    return {
      isOpen: false,
    };
  },
  methods: {
    handleMenu() {
      this.isOpen = !this.isOpen;
    },
  },
};
</script>


<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap');

span{
  font-family: Roboto;
}
</style>