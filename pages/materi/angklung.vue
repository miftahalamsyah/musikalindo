<template>
    <head>
      <title>Angklung | Musikalindo</title>
    </head>
    <div class="bg-white text-stone-900 p-5 shadow-md rounded-3xl mt-2 mb-5">
      <img src="~/assets/angklung.jpg" class="relative mb-2 max-h-48 rounded-t-3xl object-cover w-full " />
      <audio controls class="my-2 rounded-3xl mx-auto">
        <source src="~/assets/angklung.mp3" type="audio/mp3" />
        Your browser does not support the audio tag.
      </audio>
      <h2 class="text-lg font-extrabold">Angklung</h2>
      <p class="text-sm font-normal mt-2">Angklung adalah alat musik tradisional yang berasal dari Jawa Barat, terbuat dari potongan bambu. Instrumen ini terdiri dari 2 hingga 4 tabung bambu yang dihubungkan dengan tali rotan. Setiap tabung bambu diukir dan dipotong dengan teliti untuk menghasilkan nada tertentu ketika bingkai bambu digoyang. Nama "angklung" berasal dari bahasa Sunda, mengacu pada gerakan pemain angklung dan suara "klung" yang dihasilkan.</p>
      <p class="text-sm font-normal mt-2 font-semibold">Cara Memainkan</p>
      <p class="text-sm font-normal mt-2">Pemain angklung menggunakan gerakan goyangan atau getaran untuk menghasilkan suara. Setiap tabung bambu diukir dan dipotong sedemikian rupa sehingga menghasilkan nada tertentu. Angklung biasanya dimainkan dalam kelompok, di mana setiap anggota kelompok bertanggung jawab atas satu atau beberapa tabung bambu. Goyangan yang sinkron antar pemain menghasilkan harmoni yang khas dari angklung.</p>
      <p class="text-sm font-normal mt-2 font-semibold">Sejarah Angklung</p>
      <p class="text-sm font-normal mt-2">Angklung memiliki sejarah panjang di Nusantara, bahkan sebelum era Hindu. Selain ditemukan di Jawa Barat, angklung juga dikenal di daerah Sumatra Selatan, Kalimantan, Lampung, Jawa Timur, dan Jawa Tengah. Dalam lingkungan Kerajaan Sunda (abad ke-12 hingga abad ke-16), angklung digunakan dalam pemujaan terhadap Nyai Sri Pohaci sebagai lambang Dewi Sri. Selain itu, angklung juga dimainkan sebagai alat musik penggembira dalam peperangan, sesuai dengan cerita dalam Kidung Sunda.</p>
      <p class="text-sm font-normal mt-2">Perkembangan angklung di Jawa Barat dipengaruhi oleh tokoh seperti Daeng Soetigna dan Udjo Ngalagena. Pada tahun 1938, Daeng Soetigna menciptakan inovasi angklung dengan tangga nada diatonis, memungkinkannya dimainkan harmonis bersama alat musik Barat. Inovasi ini membuat angklung semakin populer dan diakui oleh UNESCO sebagai Karya Agung Warisan Budaya Lisan dan Nonbendawi Manusia pada November 2010. Udjo Ngalagena, murid Daeng Soetigna, berperan dalam mempopulerkan angklung dengan mendirikan "Saung Angklung" di Bandung, yang masih menjadi pusat kreativitas terkait angklung hingga saat ini.</p>

      <div class="sketchfab-embed-wrapper py-5"> <iframe title="Angklung" frameborder="0" class="rounded-xl mx-auto" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share width="580" height="240" src="https://sketchfab.com/models/1ac9bf54e3f24ab0a61295da4be10598/embed?ui_theme=dark"> </iframe> </div>
    </div>
    <div class="grid grid-cols-3 gap-2 w-full mb-24 block">
      <div class="col-span-1">
      </div>
      <div class="col-span-1">
      </div>
      <nuxt-link to="/materi/bonang" class="text-xs col-span-1 bg-main text-stone-50 p-3 shadow-md rounded-3xl text-center flex justify-center">
            Bonang
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

