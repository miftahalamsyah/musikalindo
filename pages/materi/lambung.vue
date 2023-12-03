<template>
    <head>
      <title>Lambung | Belajar Pencernaan</title>
    </head>
        <div class="bg-white text-stone-900 p-5 shadow-md rounded-3xl mt-2 mb-5 md:mb-24 lg:mb-24">
            <h2 class="text-lg font-extrabold">Lambung</h2>
            <p class="text-sm font-normal mt-2">Setelah makanan masuk ke dalam lambung, proses pencernaan yang kompleks dimulai. Lambung adalah organ yang memiliki peran penting dalam pencernaan makanan. Di dalam lambung, makanan mengalami pencernaan baik secara mekanik maupun kimiawi. Pencernaan mekanik terjadi berkat kontraksi otot halus yang melapisi dinding lambung, sehingga makanan dicampur dengan cairan pencernaan secara merata.</p>

            <p class="text-sm font-normal mt-2">Selain pencernaan mekanik, pencernaan kimiawi juga terjadi dalam lambung. Cairan pencernaan yang dihasilkan oleh lambung mengandung <b>enzim pepsin</b>, yang berfungsi untuk mencerna protein dalam makanan menjadi asam amino. Selain itu, cairan pencernaan juga mengandung Asam Klorida (HCl), yang memiliki peran penting dalam membunuh kuman-kuman yang mungkin masuk bersama makanan yang dikonsumsi. Selama berada dalam lambung, makanan yang telah dicerna akan disimpan selama sekitar dua jam atau bahkan lebih. Pada saat berada dalam lambung, bentuk makanan akan berubah menjadi cairan kental yang siap untuk melanjutkan proses pencernaan lebih lanjut.</p>
        </div>
        <div class="grid grid-cols-3 gap-2 w-full mb-24 block md:hidden lg:hidden">
          <nuxt-link to="/materi/esofagus" class="text-xs col-span-1 bg-neutral text-stone-50 p-3 shadow-md rounded-3xl text-center hover:bg-base-content justify-center flex">
          <svg width="17" height="17" viewBox="0 0 24 24" data-name="Flat Color" xmlns="http://www.w3.org/2000/svg" class="mr-1 icon flat-color"><path d="M17.45 2.11a1 1 0 0 0-1.05.09l-12 9a1 1 0 0 0 0 1.6l12 9a1 1 0 0 0 1.05.09A1 1 0 0 0 18 21V3a1 1 0 0 0-.55-.89Z" style="fill:#ffffff"/></svg>
          Esofagus
          </nuxt-link>
          <div class="col-span-1">
          </div>
          <nuxt-link to="/materi/usus-halus" class="text-xs col-span-1 bg-neutral text-stone-50 p-3 shadow-md rounded-3xl text-center hover:bg-base-content justify-center flex">
          Usus Halus
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

