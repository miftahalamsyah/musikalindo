<template>
    <head>
      <title>Pankreas dan Hati | Belajar Pencernaan</title>
    </head>
        <div class="bg-white text-stone-900 p-5 shadow-md rounded-3xl mt-2 mb-5 md:mb-24 lg:mb-24">
            <h2 class="text-lg font-extrabold">Pankreas dan Hati</h2>
            <p class="text-sm font-normal mt-2"><b>Pankreas</b>, organ yang terletak di antara lambung dan bagian awal usus halus, memiliki peran penting dalam pencernaan. Pankreas menghasilkan berbagai enzim pencernaan yang bertugas mencerna berbagai jenis nutrisi dalam makanan, termasuk karbohidrat, protein, dan lemak. Kemampuan pankreas untuk memecah zat-zat ini menjadi bentuk yang lebih sederhana memungkinkan tubuh untuk menyerap nutrisi tersebut dengan lebih efisien.</p>
            <p class="text-sm font-normal mt-2"><b>Hati</b> memproduksi empedu, yang merupakan cairan penting dalam pemecahan lemak dalam makanan. Empedu diproduksi oleh hati dan kemudian disimpan di dalam kantung empedu hingga diperlukan. Ketika makanan mencapai usus halus, kantung empedu melepaskan empedu ke dalam usus halus untuk membantu memecah lemak menjadi partikel-partikel kecil. Proses ini memungkinkan tubuh untuk menyerap lemak dengan lebih efisien dan memastikan bahwa nutrisi yang terkandung dalam lemak tersedia untuk digunakan oleh tubuh.</p>
        </div>
        <div class="grid grid-cols-3 gap-2 w-full mb-24 block md:hidden lg:hidden">
          <nuxt-link to="/materi/usus-halus" class="text-xs col-span-1 bg-neutral text-stone-50 p-3 shadow-md rounded-3xl align-center text-center hover:bg-base-content justify-center flex">
          <svg width="17" height="17" viewBox="0 0 24 24" data-name="Flat Color" xmlns="http://www.w3.org/2000/svg" class="mr-1 icon flat-color"><path d="M17.45 2.11a1 1 0 0 0-1.05.09l-12 9a1 1 0 0 0 0 1.6l12 9a1 1 0 0 0 1.05.09A1 1 0 0 0 18 21V3a1 1 0 0 0-.55-.89Z" style="fill:#ffffff"/></svg>
          Usus Halus
          </nuxt-link>
          <div class="col-span-1">
          </div>
          <nuxt-link to="/materi/usus-besar" class="text-xs col-span-1 bg-neutral text-stone-50 p-3 shadow-md rounded-3xl text-center hover:bg-base-content justify-center flex">
          Usus Besar
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
