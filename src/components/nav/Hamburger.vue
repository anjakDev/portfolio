<template>
  <!-- copied from: https://tailwindui.com/components/application-ui/navigation/navbars --> 
  <div class="absolute inset-y-0 right-0 flex items-center sm:hidden">
    <!-- Mobile menu button-->
    <button
      class="inline-flex items-center justify-center p-2 rounded-md text-white hover:text-green-400 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-white"
      aria-expanded="false"
    >
      <span class="sr-only">Open menu</span>
      <!-- Icon when menu is closed. -->
      <!--
            Heroicon name: menu

            Menu open: "hidden", Menu closed: "block"
          -->
      <svg
        class="block h-6 w-6"
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
        aria-hidden="true"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M4 6h16M4 12h16M4 18h16"
        />
      </svg>
      <!-- Icon when menu is open. -->
      <!--
            Heroicon name: x

            Menu open: "block", Menu closed: "hidden"
          -->
      <svg
        class="hidden h-6 w-6"
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
        aria-hidden="true"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M6 18L18 6M6 6l12 12"
        />
      </svg>
    </button>
  </div>
</template>

<script>
export default {
  name: "Hamburger"
};
</script>
