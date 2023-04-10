<template>
  

<nav id="ininav"
    class="p-3 border-gray-200 rounded bg-green-50 dark:bg-gray-800 dark:border-gray-700">
    <div id="lio" class="container flex flex-wrap items-center justify-between mx-auto">
      <p class="flex items-center hover:no-underline">
        <img src="" class="h-6 mr-3 sm:h-10" />
        <span
          class="self-center hover:text-green-600 text-xl font-semibold whitespace-nowrap dark:text-white">
          DZAKI
        </span>
      </p>

      <div class="hidden w-full md:block md:w-auto">
        <ul
          class="flex flex-col mt-4 rounded-lg text-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium md:border-0 md:bg-transparent dark:bg-gray-800 md:dark:bg-transparent dark:border-gray-700">
          <li>
            <router-link
              to="/"
			class="font-general-medium block text-left text-lg font-medium text-primary-dark dark:text-ternary-light hover:text-pink-600 dark:hover:text-pink-300  sm:mx-4 mb-2 sm:py-2 border-t-2 pt-3 sm:pt-2 sm:border-t-0 border-primary-light dark:border-secondary-dark"
			aria-label="Home"
			>Beranda
            </router-link>
          </li>
          <li>
            <router-link
            to="/contact"
			class="font-general-medium block text-left text-lg font-medium text-primary-dark dark:text-ternary-light hover:text-pink-600 dark:hover:text-pink-300  sm:mx-4 mb-2 sm:py-2 "
			aria-label="Projects"
			>Kontak
            </router-link>
          </li>
          <li>
            <router-link
            to="/about"
			class="font-general-medium block text-left text-lg font-medium text-primary-dark dark:text-ternary-light hover:text-pink-600 dark:hover:text-pink-300  sm:mx-4 mb-2 sm:py-2 border-t-2 pt-3 sm:pt-2 sm:border-t-0 border-primary-light dark:border-secondary-dark"
			aria-label="About Me"
			>Tentang
            </router-link>
          </li>
          

          <li></li>
          <li></li>

        </ul>
      </div>
    </div>
  </nav>
  

</template>

<script>
   
  </script>

<style>
#ininav{
  background-image: linear-gradient(60deg, #FFDE59 0%, #FFDE59 100%);
}

#lio{
  background-image: linear-gradient(60deg, #FFDE59 0%, #FFDE59 100%);
}



</style>
