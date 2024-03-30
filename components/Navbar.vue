<template>
  <nav class="bg-white">
    <div class="flex flex-wrap justify-between items-center mx-auto max-w-screen-xl p-4">
      <NuxtLink :to="{ path: '/', hash: 'naslovnica' }" class="flex items-center space-x-3 rtl:space-x-reverse">
        <img src="../assets/img/hplink.webp" alt="" class="w-56" />
      </NuxtLink>
      <div class="flex items-center space-x-6 rtl:space-x-reverse">
        <a href="mailto:rukavina.rudi@gmail.com"
          class="text-3xl px-3 rounded-xl text-black bg-gray-50 hover:bg-gray-200 hover:shadow-sm"><i
            class="fa fa-envelope"></i></a>
        <a href="tel:+385992053344"
          class="text-3xl px-3 rounded-xl text-black bg-green-200 hover:bg-green-400 hover:shadow-sm"><i
            class="fa fa-phone"></i></a>
      </div>
    </div>
  </nav>
  <nav class="bg-gray-50 shadow-xl overflow-x-auto text-nowrap whitespace-nowrap px-5">
    <div class="max-w-screen-xl px-4 py-3 mx-auto">
      <div class="flex items-center">
        <ul class="flex flex-row font-medium mt-0 space-x-8 rtl:space-x-reverse text-sm">
          <li>
            <NuxtLink to="/" class="text-gray-900 hover:underline">Naslovnica
            </NuxtLink>
          </li>
          <li>
            <NuxtLink to="/mojeinformacije" class="text-gray-900 hover:underline">
              Informacije i certifikati
            </NuxtLink>
          </li>

          <li>
            <button id="dropdownNavbarLinkKontakt" data-dropdown-toggle="dropdownNavbarKontakt"
              class="flex items-center justify-between w-full text-gray-900 hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 md:w-auto dark:text-white md:dark:hover:text-blue-500 dark:focus:text-white dark:hover:bg-gray-700 md:dark:hover:bg-transparent pe-5">
              Usluge

              <svg class="w-2.5 h-2.5 ms-2.5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none"
                viewBox="0 0 10 6">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                  d="m1 1 4 4 4-4" />
              </svg>
            </button>

            <div id="dropdownNavbarKontakt"
              class="z-10 hidden font-normal bg-white divide-y divide-gray-100 rounded-lg shadow w-44 dark:bg-gray-700 dark:divide-gray-600">
              <ul class="py-2 text-sm text-gray-700 dark:text-gray-200" aria-labelledby="dropdownLargeButton">
                <li class="py-1">
                  <NuxtLink to="/digitalizacija"
                    class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">
                    Digitalizacija</NuxtLink>
                </li>
              </ul>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <nav class="bg-gray-50 shadow-xl overflow-x-auto text-nowrap whitespace-nowrap px-5">
    <div class="max-w-screen-xl px-4 py-3 mx-auto">
      <div class="flex items-center">
        <ul class="flex flex-row font-medium mt-0 space-x-8 rtl:space-x-reverse text-sm">
          <li>
            <button id="dropdownNavbarLinkKontaktasddsa" data-dropdown-toggle="dropdownNavbarKontaktasddsa"
              class="flex items-center text-xl justify-between w-full text-gray-900 hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 md:w-auto dark:text-white md:dark:hover:text-blue-500 dark:focus:text-white dark:hover:bg-gray-700 md:dark:hover:bg-transparent pe-5">
              Očekivanja i predviđanja

              <svg class="w-2.5 h-2.5 ms-2.5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none"
                viewBox="0 0 10 6">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                  d="m1 1 4 4 4-4" />
              </svg>
            </button>

            <div id="dropdownNavbarKontaktasddsa"
              class="z-10 hidden font-normal bg-white divide-y divide-gray-100 rounded-lg shadow w-62 dark:bg-gray-700 dark:divide-gray-600">
              <ul class="py-2 text-sm text-gray-700 dark:text-gray-200" aria-labelledby="dropdownLargeButton">
                <li>
                  <NuxtLink to="/2024"
                    class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 font-semibold dark:hover:text-white">
                    Plan 2024</NuxtLink>
                </li>
                <hr />
                <li>
                  <NuxtLink to="/2025"
                    class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 font-semibold dark:hover:text-white">
                    Plan 2025</NuxtLink>
                </li>
                <hr />
                <li>
                  <NuxtLink to="/2026"
                    class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 font-semibold dark:hover:text-white">
                    Plan 2026</NuxtLink>
                </li>
                <hr />
                <li>
                  <NuxtLink to="/2027"
                    class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 font-semibold dark:hover:text-white">
                    Plan 2027</NuxtLink>
                </li>
                <hr />
                <li>
                  <NuxtLink to="/2028"
                    class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 font-semibold dark:hover:text-white">
                    Plan 2028</NuxtLink>
                </li>
              </ul>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <nav class="bg-gray-50 shadow-xl overflow-x-auto text-nowrap whitespace-nowrap px-5">
    <div class="max-w-screen-xl px-4 py-3 mx-auto">
      <div class="flex items-center">
        <ul class="flex flex-row font-medium mt-0 space-x-8 rtl:space-x-reverse text-sm">
          <li>
            <button id="dropdownNavbarLinkKontaktasd" data-dropdown-toggle="dropdownNavbarKontaktasd"
              class="flex items-center text-2xl justify-between w-full text-gray-900 hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 md:w-auto dark:text-white md:dark:hover:text-blue-500 dark:focus:text-white dark:hover:bg-gray-700 md:dark:hover:bg-transparent pe-5">
              Sva potrebna dokumentacija

              <svg class="w-2.5 h-2.5 ms-2.5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none"
                viewBox="0 0 10 6">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                  d="m1 1 4 4 4-4" />
              </svg>
            </button>

            <div id="dropdownNavbarKontaktasd"
              class="z-10 hidden font-normal bg-white divide-y divide-gray-100 rounded-lg shadow w-62 dark:bg-gray-700 dark:divide-gray-600">
              <ul class="py-2 text-sm text-gray-700 dark:text-gray-200" aria-labelledby="dropdownLargeButton">
                <li>
                  <a href="https://docs.google.com/document/d/13h_z4B6Vim6PfKKfmKcoRmPSJGL_7hXJ/edit?usp=sharing&ouid=116829830610241773861&rtpof=true&sd=true"
                    target="_blank"
                    class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 font-semibold dark:hover:text-white">🟢
                    Ispunjeni opći podaci</a>
                </li>
                <hr />
                <li>
                  <NuxtLink to="/Elektronicki_zapis.pdf" target="_blank"
                    class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 font-semibold dark:hover:text-white">
                    🟢 E-radna knjižica</NuxtLink>
                </li>
                <hr />
                <li>
                  <NuxtLink to="/potpore"
                    class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 font-semibold dark:hover:text-white">
                    🟢 Oprema do 10,000€</NuxtLink>
                </li>
                <hr />
                <li>
                  <NuxtLink to="/pismanamjere"
                    class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 font-semibold dark:hover:text-white">
                    🟡 Pisma namjere</NuxtLink>
                </li>
                <hr />
                <li>
                  <NuxtLink to="/preslikadiplome"
                    class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 font-semibold dark:hover:text-white">
                    🟡 Preslika diplome</NuxtLink>
                </li>
              </ul>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script setup>
import { ref } from "vue";
import { onMounted } from "vue";
import {
  initAccordions,
  initCarousels,
  initCollapses,
  initDials,
  initDismisses,
  initDrawers,
  initDropdowns,
  initModals,
  initPopovers,
  initTabs,
  initTooltips,
} from "flowbite";

// initialize components based on data attribute selectors
onMounted(() => {
  initAccordions();
  initCarousels();
  initCollapses();
  initDials();
  initDismisses();
  initDrawers();
  initDropdowns();
  initModals();
  initPopovers();
  initTabs();
  initTooltips();
});
</script>

<style scoped>
.router-link-exact-active {
  color: rgb(28, 28, 28);
  font-weight: 600;
}
</style>
