<template>
    <head>
      <title>Usus Besar | Belajar Pencernaan</title>
    </head>
        <div class="bg-white text-stone-900 p-5 shadow-md rounded-3xl mt-2 mb-5 md:mb-24 lg:mb-24">
            <h2 class="text-lg font-extrabold">Usus Besar</h2>
            <p class="text-sm font-normal mt-2">Ketika makanan mencapai usus halus, proses penting penyerapan nutrisi telah berlangsung. Pada tahap ini, hampir semua nutrisi yang dibutuhkan oleh tubuh telah diserap, meninggalkan hanya air dan sisa-sisa makanan yang tidak dapat dicerna, seperti serat atau biji-bijian. Kemudian, fase berikutnya dalam perjalanan pencernaan makanan adalah memasuki usus besar, yang merupakan bagian akhir dari sistem pencernaan manusia.</p>

            <p class="text-sm font-normal mt-2">Usus besar adalah saluran yang berfungsi untuk menyerap kembali air dari campuran makanan yang tersisa. Proses penyerapan air ini penting untuk mencegah dehidrasi dan memastikan bahwa tubuh mendapatkan sebagian besar kelembaban yang diperlukan. Sementara itu, sisa-sisa makanan yang telah diolah di usus halus dan siap untuk dikeluarkan terus bergerak melalui usus besar. Dengan panjang sekitar 1,5 meter, usus besar juga menjadi tempat bagi bakteri baik yang membantu dalam pembentukan Vitamin K. Akhir dari perjalanan pencernaan ini terletak pada rektum, di mana sisa-sisa makanan ditekan menjadi bentuk padat dan siap untuk dikeluarkan melalui anus. Keseluruhan proses ini adalah bagian penting dari menjaga kesehatan sistem pencernaan manusia dan pengeluaran limbah dari tubuh.</p>
        </div>
        <div class="grid grid-cols-3 gap-2 w-full mb-24 block md:hidden lg:hidden">
          <nuxt-link to="/materi/pankreas-dan-hati" class="text-xs col-span-1 bg-neutral text-stone-50 p-3 shadow-md rounded-3xl align-center text-center hover:bg-base-content flex leading-none tracking-tight">
          <svg width="17" height="17" viewBox="0 0 24 24" data-name="Flat Color" xmlns="http://www.w3.org/2000/svg" class="mr-1 icon flat-color"><path d="M17.45 2.11a1 1 0 0 0-1.05.09l-12 9a1 1 0 0 0 0 1.6l12 9a1 1 0 0 0 1.05.09A1 1 0 0 0 18 21V3a1 1 0 0 0-.55-.89Z" style="fill:#ffffff"/></svg>
          Pankreas dan Hati
          </nuxt-link>
          <div class="col-span-1">
          </div>
          <nuxt-link to="/materi/rektum-dan-anus" class="text-xs col-span-1 bg-neutral text-stone-50 p-3 shadow-md rounded-3xl text-center hover:bg-base-content justify-center flex">
          Rektum dan Anus
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
