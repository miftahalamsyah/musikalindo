<template>
    <head>
      <title>Sapek | Musikalindo</title>
    </head>
        <div class="bg-white text-stone-900 p-5 shadow-md rounded-3xl mt-2 mb-5">
            <img src="~/assets/sapek.jpg" class="relative mb-2 max-h-48 rounded-t-3xl object-cover w-full " />
            <audio controls class="my-2 rounded-3xl mx-auto">
              <source src="~/assets/sapek.mp3" type="audio/mp3" />
              Your browser does not support the audio tag.
            </audio>
            <h2 class="text-lg font-extrabold">Sapek</h2>
            <p class="text-sm font-normal mt-2">Sapek adalah alat musik dawai tradisional yang berasal dari Kalimantan, Indonesia. Instrumen ini memiliki ciri khas berupa badan kayu yang panjang dan diberi senar yang direntangkan di atasnya. Suara pada sapek dihasilkan dengan cara memetik atau memainkan senar menggunakan tangan atau alat pemetik khusus.</p>
            <p class="text-sm font-normal mt-2 font-semibold">Cara Memainkan</p>
            <p class="text-sm font-normal mt-2">Cara memainkan sapek melibatkan teknik memetik atau memainkan senar dengan menggunakan jari atau alat pemetik yang sering kali terbuat dari tanduk atau kayu. Pemain sapek harus memiliki keterampilan dalam mengatur ritme, dinamika, dan nuansa melalui cara memetik yang berbeda. Beberapa pemain juga menggunakan teknik pukulan atau tapping pada badan sapek untuk menciptakan variasi suara.</p>
            <p class="text-sm font-normal mt-2 font-semibold">Sejarah</p>
            <p class="text-sm font-normal mt-2">Sapek memiliki akar yang dalam dalam budaya Dayak, suku yang mendiami pulau Kalimantan. Instrumen ini sering dimainkan dalam berbagai konteks, termasuk dalam upacara adat, pertunjukan seni, dan musik tradisional Dayak. Sapek bukan hanya alat musik, tetapi juga memiliki makna simbolis dalam kehidupan masyarakat Dayak.</p>
            <p class="text-sm font-normal mt-2">Sapek dapat ditemukan di beberapa provinsi di Kalimantan, seperti Kalimantan Timur, Kalimantan Barat, dan Kalimantan Tengah. Setiap wilayah mungkin memiliki gaya dan teknik bermain sapek yang sedikit berbeda, mencerminkan keanekaragaman budaya di antara suku-suku Dayak. Penggunaan sapek juga dapat bervariasi, mulai dari pengiring dalam tarian adat hingga musik ritual.</p>
            <p class="text-sm font-normal mt-2">
            Seiring waktu, sapek juga diperkenalkan dalam konteks musik yang lebih luas di Indonesia, dan pemain sapek telah menciptakan variasi baru dalam gaya bermain dan pembuatan sapek. Meskipun demikian, sapek tetap menjadi bagian tak terpisahkan dari identitas musik tradisional Kalimantan, menyuarakan kekayaan warisan budaya masyarakat Dayak.</p>

            <div class="sketchfab-embed-wrapper py-5"> <iframe title="Sapek Guitar" frameborder="0" allowfullscreen mozallowfullscreen="true" class="rounded-xl mx-auto" webkitallowfullscreen="true" width="580" height="240"  allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/cc6775ee72d14521bdee94337dd44a73/embed?ui_theme=dark&dnt=1"> </iframe> </div>
        </div>
        <div class="grid grid-cols-3 gap-2 w-full mb-24 block">
          <nuxt-link to="/materi/rebab" class="text-xs col-span-1 bg-main p-3 shadow-md rounded-3xl align-center text-center justify-center flex">
          <svg width="17" height="17" viewBox="0 0 24 24" data-name="Flat Color" fill="currentColor" xmlns="http://www.w3.org/2000/svg" class="mr-1 icon flat-color"><path d="M17.45 2.11a1 1 0 0 0-1.05.09l-12 9a1 1 0 0 0 0 1.6l12 9a1 1 0 0 0 1.05.09A1 1 0 0 0 18 21V3a1 1 0 0 0-.55-.89Z"/></svg>
          Rebab
          </nuxt-link>
          <div class="col-span-1">
          </div>
          <nuxt-link to="/materi/saron" class="text-xs col-span-1 bg-main text-stone-50 p-3 shadow-md rounded-3xl text-center  justify-center flex">
          Saron
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
