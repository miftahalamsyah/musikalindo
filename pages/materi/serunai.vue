<template>
    <head>
      <title>Serunai | Musikalindo</title>
    </head>
        <div class="bg-white text-stone-900 p-5 shadow-md rounded-3xl mt-2 mb-5">
            <img src="~/assets/serunai.jpg" class="relative mb-2 max-h-48 rounded-t-3xl object-cover w-full " />
            <audio controls class="my-2 rounded-3xl mx-auto">
              <source src="~/assets/serunai.mp3" type="audio/mp3" />
              Your browser does not support the audio tag.
            </audio>
            <h2 class="text-lg font-extrabold">Serunai</h2>
            <p class="text-sm font-normal mt-2">Serunai adalah alat musik tiup yang berasal dari Sumatra, Indonesia. Instrumen ini termasuk dalam kelompok alat musik tiup tradisional yang sering digunakan dalam berbagai upacara adat dan acara keagamaan di masyarakat Minangkabau. Serunai terbuat dari kayu dan memiliki bentuk yang panjang, dengan lubang suara di bagian atas yang digunakan untuk meniup.</p>
            <p class="text-sm font-normal mt-2 font-semibold">Cara Memainkan</p>
            <p class="text-sm font-normal mt-2">Cara memainkan serunai melibatkan meniup udara melalui lubang suara di bagian atas instrumen. Pemain serunai harus memiliki kendali yang baik atas teknik pernafasan untuk menghasilkan suara yang khas dan dapat diatur dalam berbagai nada. Serunai sering dimainkan dalam ansambel dengan instrumen-instrumen tradisional lainnya, menciptakan musik yang khas dari daerah Minangkabau.</p>
            <p class="text-sm font-normal mt-2 font-semibold">Sejarah</p>
            <p class="text-sm font-normal mt-2">Serunai memiliki sejarah yang panjang dan perkiraan awal penggunaannya dapat ditelusuri hingga berabad-abad yang lalu. Meskipun tidak ada catatan spesifik tentang tahun-tahun tertentu, serunai diyakini telah menjadi bagian integral dari budaya Minangkabau di Sumatra sejak zaman kuno.</p>
            <p class="text-sm font-normal mt-2">Pada perkiraan awal penggunaannya, serunai menjadi alat musik yang penting dalam berbagai upacara adat, upacara keagamaan, dan perayaan tradisional masyarakat Minangkabau. Keunikan suara serunai dan peranannya dalam menyemarakkan berbagai acara kehidupan sehari-hari membuatnya menjadi instrumen yang dihargai dan dilestarikan dari generasi ke generasi. Keunikan suara serunai dan perannya dalam konteks budaya dan keagamaan telah menjadikannya sebagai salah satu simbol identitas kultural masyarakat Minangkabau. Meskipun serunai umumnya terkait dengan tradisi Sumatra, instrumen ini juga telah menarik minat di luar Indonesia sebagai bagian dari keragaman warisan musik Nusantara.</p>
        </div>
        <div class="grid grid-cols-3 gap-2 w-full mb-24 block">
          <nuxt-link to="/materi/saron" class="text-xs col-span-1 bg-main p-3 shadow-md rounded-3xl align-center text-center justify-center flex">
          <svg width="17" height="17" viewBox="0 0 24 24" data-name="Flat Color" xmlns="http://www.w3.org/2000/svg" class="mr-1 icon flat-color"><path d="M17.45 2.11a1 1 0 0 0-1.05.09l-12 9a1 1 0 0 0 0 1.6l12 9a1 1 0 0 0 1.05.09A1 1 0 0 0 18 21V3a1 1 0 0 0-.55-.89Z"/></svg>
          Saron
          </nuxt-link>
          <div class="col-span-1">
          </div>
          <div class="col-span-1">
          </div>
        </div>
  </template>

  <script setup lang="ts">
    definePageMeta({
      layout: 'materi'
    })
</script>
  <style scoped>
  </style>
