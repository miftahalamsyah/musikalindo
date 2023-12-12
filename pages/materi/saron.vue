<template>
    <head>
      <title>Saron | Musikalindo</title>
    </head>
        <div class="bg-white text-stone-900 p-5 shadow-md rounded-3xl mt-2 mb-5">
            <img src="~/assets/saron.jpg" class="relative mb-2 max-h-48 rounded-t-3xl object-cover w-full " />
            <audio controls class="my-2 rounded-3xl mx-auto" width="100%">
              <source src="~/assets/saron.mp3" type="audio/mp3" />
              Your browser does not support the audio tag.
            </audio>
            <h2 class="text-lg font-extrabold">Saron</h2>
            <p class="text-sm font-normal mt-2">Saron adalah alat musik tradisional Indonesia yang termasuk dalam kelompok gamelan. Gamelan sendiri adalah ansambel musik tradisional Jawa dan Bali yang terdiri dari berbagai instrumen perkusi dan melodis. Saron memiliki bentuk seperti kotak terbuka dan biasanya terbuat dari kayu. Instrumen ini memiliki lempengan logam yang direntangkan di atasnya, dan suara dihasilkan dengan cara memukul lempengan-logam tersebut.</p>
            <p class="text-sm font-normal mt-2 font-semibold">Cara Memainkan</p>
            <p class="text-sm font-normal mt-2">Cara memainkan saron melibatkan pemukulan lempengan-logam dengan menggunakan pemukul yang disebut "tabuh." Pemain saron harus memiliki keterampilan dalam mengontrol kekuatan pukulan untuk menghasilkan suara yang sesuai dengan karakteristik musik yang dimainkan. </p>
            <p class="text-sm font-normal mt-2 font-semibold">Sejarah</p>
            <p class="text-sm font-normal mt-2">Tidak ada catatan yang pasti tentang tahun-tahun spesifik terkait dengan sejarah perkembangan saron. Sejarah musik gamelan, termasuk penggunaan saron, seringkali berkaitan dengan zaman kerajaan di Jawa yang tidak selalu memiliki catatan tertulis yang jelas. Penggunaan dan perkembangan saron telah menjadi bagian integral dari musik tradisional Indonesia selama berabad-abad, mungkin telah dimainkan dan dikembangkan sejak abad pertengahan atau bahkan sebelumnya.</p>
            <p class="text-sm font-normal mt-2">Meskipun demikian, saron telah menjadi salah satu instrumen yang paling penting dalam gamelan Jawa dan Bali, menggambarkan peran yang kuat dalam mengisi ruang musik tradisional sejak era kerajaan di Indonesia. Pada era modern, peran saron dalam gamelan tetap utuh dan dihargai, menjadi bagian yang tak terpisahkan dari warisan musik Indonesia.</p>

            <div class="sketchfab-embed-wrapper py-5"> <iframe title="Saron" frameborder="0" class="rounded-xl mx-auto" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share width="100%"  height="240" src="https://sketchfab.com/models/a4026aa0998e4e2b8460b339b0f2666b/embed?ui_theme=dark"> </iframe> </div>
        </div>
        <div class="grid grid-cols-3 gap-2 w-full mb-24 block">
          <nuxt-link to="/materi/sapek" class="text-xs col-span-1 bg-main p-3 shadow-md rounded-3xl align-center text-center  justify-center flex">
          <svg width="17" height="17" viewBox="0 0 24 24" fill="currentColor"  data-name="Flat Color" xmlns="http://www.w3.org/2000/svg" class="mr-1 icon flat-color"><path d="M17.45 2.11a1 1 0 0 0-1.05.09l-12 9a1 1 0 0 0 0 1.6l12 9a1 1 0 0 0 1.05.09A1 1 0 0 0 18 21V3a1 1 0 0 0-.55-.89Z"/></svg>
          Sapek
          </nuxt-link>
          <div class="col-span-1">
          </div>
          <nuxt-link to="/materi/serunai" class="text-xs col-span-1 bg-main text-stone-50 p-3 shadow-md rounded-3xl text-center justify-center flex">
          Serunai
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
