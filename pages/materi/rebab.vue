<template>
    <head>
      <title>Rebab | Musikalindo</title>
    </head>
        <div class="bg-white text-stone-900 p-5 shadow-md rounded-3xl mt-2 mb-5">
            <img src="~/assets/rebab.jpg" class="relative mb-2 max-h-48 rounded-t-3xl object-cover w-full " />
            <audio controls class="my-2 rounded-3xl mx-auto">
              <source src="~/assets/rebab.mp3" type="audio/mp3" />
              Your browser does not support the audio tag.
            </audio>
            <h2 class="text-lg font-extrabold">Rebab</h2>
            <p class="text-sm font-normal mt-2">Rebab adalah alat musik dawai gesek tradisional yang berasal dari Timur Tengah dan tersebar di berbagai budaya, termasuk Indonesia. Instrumen ini terdiri dari badan yang terbuat dari kayu dan memiliki dua atau tiga senar yang direntangkan di atasnya. Suara pada rebab dihasilkan dengan cara memetik atau memainkan senar menggunakan busur.</p>
            <p class="text-sm font-normal mt-2 font-semibold">Cara Memainkan</p>
            <p class="text-sm font-normal mt-2">Cara memainkan rebab melibatkan penggunaan busur untuk menghasilkan getaran pada senar, menghasilkan suara yang khas dan penuh nuansa. Pemain rebab harus memiliki keterampilan dalam mengontrol busur dan menghasilkan nada yang sesuai dengan karakteristik musik yang dimainkan. Rebab sering digunakan dalam berbagai jenis musik tradisional dan sering menjadi bagian penting dari ansambel.</p>
            <p class="text-sm font-normal mt-2 font-semibold">Sejarah</p>
            <p class="text-sm font-normal mt-2">Rebab memiliki sejarah yang panjang, dengan akar yang dapat ditelusuri kembali ke zaman pertengahan. Instrumen ini diperkirakan pertama kali muncul di wilayah Timur Tengah pada abad ke-8. Rebab kemudian menyebar ke berbagai belahan dunia, termasuk Asia, Afrika, dan Eropa. Di Indonesia, rebab menjadi salah satu instrumen utama dalam berbagai jenis musik tradisional, terutama dalam gamelan.</p>
            <p class="text-sm font-normal mt-2">
            Saat membicarakan Indonesia, rebab sering diasosiasikan dengan musik tradisional Jawa dan Bali. Di Jawa, rebab sering digunakan dalam gamelan Jawa, yang merupakan ansambel musik tradisional dari Jawa Tengah dan Jawa Timur. Di Bali, rebab juga merupakan instrumen penting dalam musik gamelan Bali. Keduanya adalah provinsi di Indonesia yang memiliki warisan seni dan budaya yang kaya, dan rebab memainkan peran sentral dalam menyuarakan keindahan musik tradisional di wilayah ini.</p>

            <div class="sketchfab-embed-wrapper py-5"> <iframe title="Rebab (ADR (KLTN) CHEISA 25)" frameborder="0" class="mx-auto rounded-xl" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share width="580" height="240" src="https://sketchfab.com/models/ec7a536fe0284f9a8f6d39e058f71757/embed?ui_theme=dark"> </iframe> </div>

        </div>
        <div class="grid grid-cols-3 gap-2 w-full mb-24 block">
          <nuxt-link to="/materi/gong" class="text-xs col-span-1 bg-main p-3 shadow-md rounded-3xl align-center text-center justify-center flex">
          <svg width="17" height="17" viewBox="0 0 24 24" data-name="Flat Color" xmlns="http://www.w3.org/2000/svg" class="mr-1 icon flat-color"><path d="M17.45 2.11a1 1 0 0 0-1.05.09l-12 9a1 1 0 0 0 0 1.6l12 9a1 1 0 0 0 1.05.09A1 1 0 0 0 18 21V3a1 1 0 0 0-.55-.89Z"/></svg>
          Gong
          </nuxt-link>
          <div class="col-span-1">
          </div>
          <nuxt-link to="/materi/sapek" class="text-xs col-span-1 bg-main p-3 shadow-md rounded-3xl text-center justify-center flex">
          Sapek
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
