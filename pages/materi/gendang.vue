<template>
    <head>
      <title>Gendang | Musikalindo</title>
    </head>
        <div class="bg-white text-stone-900 p-5 shadow-md rounded-3xl mt-2 mb-5">
            <img src="~/assets/gendang.jpg" class="relative mb-2 max-h-48 rounded-t-3xl object-cover w-full " />
            <audio controls class="my-2 rounded-3xl mx-auto">
              <source src="~/assets/gendang.mp3" type="audio/mp3" />
              Your browser does not support the audio tag.
            </audio>
            <h2 class="text-lg font-extrabold">Gendang</h2>
            <p class="text-sm font-normal mt-2">Gendang adalah alat musik perkusi yang sering digunakan dalam berbagai budaya di seluruh dunia. Di Indonesia, gendang merupakan instrumen yang sangat penting dalam berbagai jenis musik tradisional, terutama dalam gamelan, musik daerah, dan upacara adat. Gendang umumnya terbuat dari bahan kulit yang direntangkan di atas suatu rangka, dan suaranya dihasilkan dengan cara dipukul.</p>
            <p class="text-sm font-normal mt-2 font-semibold">Cara Memainkan</p>
            <p class="text-sm font-normal mt-2">Cara memainkan gendang melibatkan penggunaan dua tangan atau pemukul, yang digunakan untuk memukul kulit gendang dengan berbagai teknik seperti tepukan, gesekan, atau ketukan yang kompleks. Pemain gendang harus memiliki keterampilan ritmis yang baik dan memahami pola-pola yang khas untuk setiap jenis musik yang dimainkan. Gendang sering dimainkan secara ensemble dalam kelompok musik, memberikan ritme dan dinamika yang kuat untuk seluruh ansambel.</p>
            <p class="text-sm font-normal mt-2 font-semibold">Sejarah</p>
            <p class="text-sm font-normal mt-2">Gendang memiliki sejarah yang panjang dan luas di berbagai budaya di seluruh dunia. Di Indonesia, gendang telah digunakan sejak zaman kerajaan dan menjadi bagian tak terpisahkan dari warisan musik Nusantara. Jenis dan bentuk gendang bervariasi antar daerah dan suku di Indonesia, mencerminkan kekayaan budaya yang beragam.</p>
            <p class="text-sm font-normal mt-2">
            Gendang tidak hanya digunakan dalam konteks musik, tetapi juga seringkali memegang peran penting dalam upacara keagamaan, upacara adat, dan ritual kebudayaan. Di era modern, gendang terus digunakan dalam berbagai bentuk musik, termasuk musik populer dan dunia, tetapi tetap mempertahankan nilai dan identitas tradisionalnya. Gendang terus menjadi simbol keberagaman dan kekayaan warisan musik di Indonesia serta berkontribusi pada keindahan dan kekuatan musik Nusantara.</p>
            <div class="sketchfab-embed-wrapper py-5"> <iframe title="Gendang Bulo" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" class="rounded-xl mx-auto" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share width="580" height="240" src="https://sketchfab.com/models/21c60cffafad447d83a7314926241cec/embed?ui_theme=dark"> </iframe> </div>
        </div>
        <div class="grid grid-cols-3 gap-2 w-full mb-24 block">
          <nuxt-link to="/materi/bonang" class="text-xs col-span-1 bg-main p-3 shadow-md rounded-3xl align-center text-center justify-center flex">
          <svg width="17" height="17" viewBox="0 0 24 24" data-name="Flat Color" xmlns="http://www.w3.org/2000/svg" class="mr-1 icon flat-color"><path d="M17.45 2.11a1 1 0 0 0-1.05.09l-12 9a1 1 0 0 0 0 1.6l12 9a1 1 0 0 0 1.05.09A1 1 0 0 0 18 21V3a1 1 0 0 0-.55-.89Z"/></svg>
          Bonang
          </nuxt-link>
          <div class="col-span-1">
          </div>
          <nuxt-link to="/materi/gong" class="text-xs col-span-1 bg-main p-3 shadow-md rounded-3xl text-center justify-center flex">
          Gong
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

