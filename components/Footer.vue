<template>
  <!-- <footer class="bg-white ">
    <div class=" grid grid-cols-2 gap-2 lg:grid-cols-6  ring-primary/5  px-8 py-3 pt-6 bg-gray-100">



      <div class="flex justify-center my-1 lg:mb-4 space-y-4 sm:flex-row sm:justify-center sm:space-y-0 sm:space-x-4">
        <a href="tel:+385917865619"
          class="inline-flex justify-center items-center py-3 px-5 text-base font-medium  w-full max-w-md text-center rounded border border-slate-800 p-1 bg-white text-slate-800 hover:bg-gray-50 hover:border-slate-900 focus:ring-4 focus:ring-gray-100  hover:shadow-lg">
          <i class='fa fa-phone'> Nazovite nas</i>
        </a>
      </div>
      <div class="flex justify-center my-1 lg:mb-4 space-y-4 sm:flex-row sm:justify-center sm:space-y-0 sm:space-x-4">
        <a href="mailto:poduke@parallel.hr"
          class="inline-flex justify-center items-center py-3 px-5 text-base font-medium  w-full max-w-md text-center rounded border border-slate-800 bg-white text-slate-800 hover:bg-gray-50  focus:ring-4 focus:ring-gray-100  hover:shadow-lg">
          <i class='fa fa-envelope text-nowrap'> <span class='text-sm'> Pošaljite email</span></i>
        </a>
      </div>
      <div class="flex justify-center my-1 lg:mb-4 space-y-4 sm:flex-row sm:justify-center sm:space-y-0 sm:space-x-4">
        <a href='https://www.facebook.com/poduke.parallel' target='_blank'
          class="inline-flex justify-center items-center py-3 px-5 text-base font-medium  w-full max-w-md text-center rounded border border-slate-800 bg-white text-slate-800 hover:bg-gray-50 focus:ring-4 focus:ring-gray-100  hover:shadow-lg">
          <i class='fa fa-facebook'>acebook</i> </a>
      </div>
      <div class="flex justify-center my-1 lg:mb-4 space-y-4 sm:flex-row sm:justify-center sm:space-y-0 sm:space-x-4">
        <a href='https://www.instagram.com/poduke.parallel' target='_blank'
          class="inline-flex justify-center items-center py-3 px-5 text-base font-medium  w-full max-w-md text-center rounded border border-slate-800 bg-white text-slate-800 hover:bg-gray-50 focus:ring-4 focus:ring-gray-100  hover:shadow-lg">
          <i class='fa fa-instagram'> Instagram</i>
        </a>
      </div>
      <div class="flex justify-center my-1 lg:mb-4 space-y-4 sm:flex-row sm:justify-center sm:space-y-0 sm:space-x-4">
        <a href="https://maps.app.goo.gl/9dFa9f6sUkVuHxRD9" target='_blank'
          class="inline-flex justify-center items-center py-3 px-5 text-base font-medium  w-full max-w-md text-center rounded border border-slate-800 bg-white text-slate-800 hover:bg-gray-50 focus:ring-4 focus:ring-gray-100  hover:shadow-lg">
          <i class='fa fa-map-marker'> Google Maps</i> </a>
      </div>
      <div class="flex justify-center my-1 lg:mb-4 space-y-4 sm:flex-row sm:justify-center sm:space-y-0 sm:space-x-4">
        <NuxtLink to='/radnovrijeme'
          class="inline-flex justify-center items-center py-3 px-5 text-base font-medium  w-full max-w-md text-center rounded border border-slate-800 bg-white text-slate-800 hover:bg-gray-50 focus:ring-4 focus:ring-gray-100  hover:shadow-lg">
          <a href=""><i class='fa fa-calendar'> Radno vrijeme</i></a>
        </NuxtLink>
      </div>



    </div>
    <div class="mx-auto w-full max-w-screen-xl px-4 pb-3 lg:pb-6">

      <hr class=" py-2 border-gray-200 w-full " />
      <div class=" grid-cols-2 flex justify-evenly gap-8 sm:gap-6 sm:grid-cols-3">

        <div>
          <ul class="text-gray-500 font-medium">
            <li class="">
              <a href="https://www.facebook.com/poduke.parallel" class="hover:underline ">Politika Privatnosti</a>
            </li>
          </ul>
        </div>
        <div>
          <ul class="text-gray-500  font-medium">
            <li class=''>
                           <NuxtLink to="/digitalizacija" class="hover:underline">Uvjeti korištenja</a>
            </li>

          </ul>
        </div>
      </div>
      <hr class="my-4 border-gray-200 sm:mx-auto  lg:my-6" />
      <div class=" items-center text-center justify-center">
        <span class="text-sm text-gray-500 sm:text-center ">© 2024 <a href="/" class="hover:underline">Parallel d.o.o.</a>
          Sva prava zadržana.

        </span>
      </div>

    </div>
  </footer> -->

  <footer class="bg-white">
    <div class="container mx-auto px-8">
      <div class="w-full flex flex-col md:flex-row py-6">
        <div class="flex-1 mb-6 text-black">
          <a class="text-pink-600 no-underline hover:no-underline font-bold text-2xl lg:text-4xl" href="#">
            <!--Icon from: http://www.potlabicons.com/ -->
            <img src="../assets/img/hyperlinklogo3.webp" alt="" class="w-32  inline-block me-3 rounded-xl">

          </a>
        </div>
        <div class="flex-1">
          <p class="uppercase text-gray-500 md:mb-6">Hyperlink</p>
          <ul class="list-reset mb-6">
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/" class="no-underline hover:underline text-gray-800 hover:text-pink-500">
                Naslovnica
              </NuxtLink>
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/mojeinformacije" class="no-underline hover:underline text-gray-800 hover:text-pink-500">
                Moje informacije
              </NuxtLink>
            </li>

            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">
                Usluge digitalizacije poslovanja</NuxtLink>
            </li>
          </ul>
        </div>
        <div class="flex-1">
          <p class="uppercase text-gray-500 md:mb-6">Usluge digitalizacije poslovanja</p>
          <ul class="list-reset mb-6">
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">
                Frizerski salon | Salon ljepote
              </NuxtLink>
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">
                Teretana | Fitness
                center
              </NuxtLink>
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">
                Taxi služba
              </NuxtLink>
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">
                Ugostiteljski objekt - Caffe bar
              </NuxtLink>
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">
                Ugostiteljski objekt - Restoran
              </NuxtLink>
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">
                Rent a car | Rent a van
              </NuxtLink>
            </li>
          </ul>
        </div>
        <div class="flex-1">
          <p class="uppercase text-gray-500 md:mb-6">Marketing</p>
          <ul class="list-reset mb-6">
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">
                Izrada | Instrukcije i pomoć s vođenjem društvenih mreža
              </NuxtLink>
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">
                Izrada | Instrukcije i pomoć s google oglašavanjem
              </NuxtLink>
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">
                Izrada | Instrukcije i pomoć s facebook oglašavanjem
              </NuxtLink>
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">
                Izrada kratkih glazbenih videa
              </NuxtLink>
            </li>

          </ul>
        </div>

        <div class="flex-1">
          <p class="uppercase text-gray-500 md:mb-6">Grafički dizajn</p>
          <ul class="list-reset mb-6">
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">
                Razvoj dizajna logotipa</NuxtLink>
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">
                Razvoj dizajna i provedba izrade
                letaka</NuxtLink>
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">
                Razvoj dizajna i provedba izrade
                vizitki</NuxtLink>
            </li>

          </ul>
        </div>
        <div class="flex-1">
          <p class="uppercase text-gray-500 md:mb-6">Očekivanja i predviđanja</p>
          <ul class="list-reset mb-6">
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">Za
                2024. godinu</NuxtLink>
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">Za
                2025. godinu</NuxtLink>
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">Za
                2026. godinu</NuxtLink>
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">Za
                2027. godinu</NuxtLink>
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <NuxtLink to="/digitalizacija" class="no-underline hover:underline text-gray-800 hover:text-pink-500">Za
                2028. godinu</NuxtLink>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>