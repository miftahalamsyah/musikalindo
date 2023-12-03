<template>
    <head>
      <title>Esofagus | Belajar Pencernaan</title>
    </head>
        <div class="bg-white text-stone-900 p-5 shadow-md rounded-3xl mt-2 mb-5 md:mb-24 lg:mb-24">
            <h2 class="text-lg font-extrabold">Esofagus</h2>
            <p class="text-sm font-normal mt-2">Di bagian belakang mulut kita, terdapat dua saluran yang memiliki peran penting dalam proses pencernaan. Yang pertama adalah saluran yang menuju saluran napas, yang kita kenal sebagai tenggorokan. Tenggorokan berfungsi untuk membawa udara ke paru-paru, memungkinkan kita bernapas. Saluran kedua adalah kerongkongan, yang merupakan jalur menuju saluran pencernaan. Ketika kita makan, ada mekanisme yang melindungi saluran napas. <b>Epiglotis</b>, sebuah katup kecil, akan menutup tenggorokan untuk mencegah makanan masuk ke dalam saluran napas. Hal ini memastikan bahwa makanan hanya masuk ke dalam esofagus.</p>

            <p class="text-sm font-normal mt-2">Esofagus adalah saluran berotot yang menghubungkan mulut dengan lambung. Di dalam esofagus, terdapat lendir yang membantu melicinkan makanan, sehingga makanan dapat meluncur lebih mudah. Selain itu, gerakan <b>peristalsis</b> yang dihasilkan oleh otot-otot esofagus membantu mendorong makanan dari mulut ke lambung. Dengan koordinasi yang baik antara epiglotis, esofagus, dan otot-otot yang terlibat, makanan dapat bergerak dengan lancar melalui saluran pencernaan kita menuju lambung, di mana proses pencernaan lebih lanjut akan terjadi.</p>
        </div>
        <div class="grid grid-cols-3 gap-2 w-full mb-24 block md:hidden lg:hidden">
          <nuxt-link to="/materi/mulut" class="text-xs col-span-1 bg-neutral text-stone-50 p-3 shadow-md rounded-3xl text-center hover:bg-base-content justify-center flex">
            <svg width="17" height="17" viewBox="0 0 24 24" data-name="Flat Color" xmlns="http://www.w3.org/2000/svg" class="mr-1 icon flat-color"><path d="M17.45 2.11a1 1 0 0 0-1.05.09l-12 9a1 1 0 0 0 0 1.6l12 9a1 1 0 0 0 1.05.09A1 1 0 0 0 18 21V3a1 1 0 0 0-.55-.89Z" style="fill:#ffffff"/></svg>
            Mulut
          </nuxt-link>
          <div class="col-span-1">
          </div>
          <nuxt-link to="/materi/lambung" class="text-xs col-span-1 bg-neutral text-stone-50 p-3 shadow-md rounded-3xl text-center hover:bg-base-content justify-center flex">
          Lambung
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

