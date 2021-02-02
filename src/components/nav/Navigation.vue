<template>
  <nav class="bg-yellow-300 w-full mx-auto px-2 sm:px-6 lg:px-8">
    <div class="sticky flex flex-none content-center space-between" role="menu">
      <Hamburger />
      <div class="flex-none pl-4 sm:pl-6 xl:pl-8 flex items-center">
        <a href="#" class="block px-4 py-4" role="menuitem">
          <span class="sr-only">AnjanasCode Logo</span>
          <img
            class="h-20 w-20 rounded-full"
            src="../../assets/AnjanasCode.png"
          />
        </a>
      </div>
      <div
        class="flex-auto flex items-center justify-end px-4 sm:px-6 lg:mx-6 lg:px-0 xl:mx-8"
      >
        <div class="hidden sm:block sm:ml-6">
          <a
            href="#"
            class="text-yellow-900 px-3 py-2 rounded-md text-md font-medium"
            >About me.</a
          >
          <a
            href="#"
            class="text-white px-3 py-2 rounded-md text-md font-medium"
            >Say hi.</a
          >
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
import Hamburger from "./Hamburger";

export default {
  name: "Navigation",
  components: {
    Hamburger
  }
};
</script>
