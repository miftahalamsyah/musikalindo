<template>
    <head>
      <title>Usus Halus | Belajar Pencernaan</title>
    </head>
        <div class="bg-white text-stone-900 p-5 shadow-md rounded-3xl mt-2 mb-5 md:mb-24 lg:mb-24">
            <h2 class="text-lg font-extrabold">Usus Halus</h2>
            <p class="text-sm font-normal mt-2">Usus halus memiliki panjang yang luar biasa, yakni sekitar enam meter, menjadikannya organ terpanjang dalam sistem pencernaan manusia. Meskipun panjangnya yang mencengangkan, diameternya hanya sekitar 2 hingga 3 centimeter, sehingga disebut sebagai usus halus atau usus kecil. Organ ini memainkan peran penting dalam proses pencernaan kimiawi, yang berlangsung lebih lama daripada di organ pencernaan lainnya. Saat makanan mencapai usus halus, proses pencernaan kimiawi berlanjut, dan molekul nutrien siap untuk diserap tubuh. Di dalam usus halus, terdapat struktur berbentuk lipatan kecil seperti jari yang disebut <b>villi</b>, yang bertugas memperluas area penyerapan nutrien.</p>

            <p class="text-sm font-normal mt-2"><b>Villi</b> ini membantu dalam penyerapan nutrisi dengan memperbesar permukaan penyerapan di dalam usus halus. Sehingga, sebagian besar nutrien yang kita butuhkan untuk pertumbuhan dan energi diserap melalui permukaan villi ini. Dengan demikian, usus halus merupakan bagian penting dalam sistem pencernaan, yang memungkinkan tubuh manusia untuk mendapatkan nutrisi yang diperlukan dari makanan yang dikonsumsi.</p>
        </div>
        <div class="grid grid-cols-3 gap-2 w-full mb-24 block md:hidden lg:hidden">
          <nuxt-link to="/materi/lambung" class="text-xs col-span-1 bg-neutral text-stone-50 p-3 shadow-md rounded-3xl align-center text-center hover:bg-base-content justify-center flex leading-none tracking-tight">
          <svg width="17" height="17" viewBox="0 0 24 24" data-name="Flat Color" xmlns="http://www.w3.org/2000/svg" class="mr-1 icon flat-color"><path d="M17.45 2.11a1 1 0 0 0-1.05.09l-12 9a1 1 0 0 0 0 1.6l12 9a1 1 0 0 0 1.05.09A1 1 0 0 0 18 21V3a1 1 0 0 0-.55-.89Z" style="fill:#ffffff"/></svg>
                Lambung
          </nuxt-link>
          <div class="col-span-1">
          </div>
          <nuxt-link to="/materi/pankreas-dan-hati" class="text-xs col-span-1 bg-neutral text-stone-50 p-3 shadow-md rounded-3xl text-center hover:bg-base-content justify-center flex leading-none tracking-tight">
          Pankreas dan Hati
          <svg width="17" height="17" viewBox="0 0 24 24" data-name="Flat Color" fill="currentColor" xmlns="http://www.w3.org/2000/svg" class="ml-1 icon flat-color"><path d="m18.6 11.2-12-9A1 1 0 0 0 5 3v18a1 1 0 0 0 .55.89 1 1 0 0 0 1-.09l12-9a1 1 0 0 0 0-1.6Z"/></svg>
          </nuxt-link>
        </div>
  </template>

  <script setup lang="ts">
    definePageMeta({
      layout: 'materi'
    })
</script>
  <style scoped>
  </style>
