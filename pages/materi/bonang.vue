<template>
    <head>
      <title>Bonang | Musikalindo</title>
    </head>
        <div class="bg-white text-stone-900 p-5 shadow-md rounded-3xl mt-2 mb-5">
            <img src="~/assets/bonang.jpg" class="relative mb-2 max-h-48 rounded-t-3xl object-cover w-full " />
            <audio controls class="my-2 rounded-3xl mx-auto" width="100%" >
              <source src="~/assets/bonang.mp3" type="audio/mp3" />
              Your browser does not support the audio tag.
            </audio>
            <h2 class="text-lg font-extrabold">Bonang</h2>
            <p class="text-sm font-normal mt-2">Bonang adalah alat musik perkusi tradisional yang berasal dari Indonesia, khususnya Jawa. Bonang merupakan salah satu instrumen yang sering digunakan dalam gamelan, sebuah ansambel musik tradisional Jawa. Instrumen ini terdiri dari serangkaian gong kecil yang disusun dalam rangkaian horizontal atau vertikal, biasanya terbuat dari logam seperti perunggu.</p>
            <p class="text-sm font-normal mt-2 font-semibold">Cara Memainkan</p>
            <p class="text-sm font-normal mt-2">Cara memainkan bonang melibatkan penggunaan dua pemukul atau alu, yang digunakan untuk memukul bagian atas gong yang datar. Pemain bonang harus memiliki keterampilan yang baik dalam mengatur ritme dan dinamika, karena bonang memainkan peran penting dalam menyediakan struktur ritmis dalam ansambel gamelan. Setiap gong pada bonang menghasilkan suara yang berbeda, dan kombinasi dari gong-gong ini menciptakan pola-pola yang kompleks dan kaya.</p>
            <p class="text-sm font-normal mt-2 font-semibold">Sejarah</p>
            <p class="text-sm font-normal mt-2">Bonang memiliki sejarah panjang dalam musik tradisional Indonesia. Instrumen ini telah ada sejak zaman kerajaan di Jawa dan menjadi bagian integral dari gamelan, sebuah ansambel musik yang mencakup berbagai instrumen perkusi dan melodis. Bonang digunakan dalam berbagai konteks musik, baik dalam upacara keagamaan, pementasan seni tradisional, maupun sebagai bagian dari hiburan di istana kerajaan.</p>
            <p class="text-sm font-normal mt-2">
            Seiring waktu, bonang mengalami perkembangan dalam teknik pembuatan dan gaya memainkannya. Berbagai jenis bonang telah dikembangkan, termasuk bonang panerus yang lebih kecil dan bonang barung yang lebih besar. Sejarah bonang mencerminkan kekayaan budaya Indonesia dan peran pentingnya dalam mempertahankan warisan musik tradisional. Hari ini, bonang masih digunakan dan dihargai dalam berbagai pertunjukan musik tradisional di Indonesia dan di seluruh dunia.</p>

            <div class="sketchfab-embed-wrapper py-5"> <iframe title="Gamelan Bonang" class="rounded-xl mx-auto" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share width="100%"  height="240" src="https://sketchfab.com/models/62d902057a6d4e358dc5b5832a6b5994/embed?ui_theme=dark"> </iframe> </div>
        </div>
        <div class="grid grid-cols-3 gap-2 w-full mb-24 block">
          <nuxt-link to="/materi/angklung" class="text-xs col-span-1 bg-main p-3 shadow-md rounded-3xl align-center text-center justify-center flex">
            <svg width="17" height="17" viewBox="0 0 24 24" data-name="Flat Color" xmlns="http://www.w3.org/2000/svg" class="mr-1 icon flat-color"><path d="M17.45 2.11a1 1 0 0 0-1.05.09l-12 9a1 1 0 0 0 0 1.6l12 9a1 1 0 0 0 1.05.09A1 1 0 0 0 18 21V3a1 1 0 0 0-.55-.89Z"/></svg>
            Angklung
          </nuxt-link>
          <div class="col-span-1">
          </div>
          <nuxt-link to="/materi/gendang" class="text-xs col-span-1 bg-main p-3 shadow-md rounded-3xl text-center justify-center flex">
          Gendang
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

