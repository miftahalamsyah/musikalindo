<template>
    <head>
      <title>Gong | Musikalindo</title>
    </head>
        <div class="bg-white text-stone-900 p-5 shadow-md rounded-3xl mt-2 mb-5">
            <img src="~/assets/gong.webp" class="relative mb-2 max-h-48 rounded-t-3xl object-cover w-full " />
            <audio controls class="my-2 rounded-3xl mx-auto">
              <source src="~/assets/gong.mp3" type="audio/mp3" />
              Your browser does not support the audio tag.
            </audio>
            <h2 class="text-lg font-extrabold">Gong</h2>
            <p class="text-sm font-normal mt-2">Gong adalah alat musik perkusi yang terdiri dari cakram logam besar dengan tepi melengkung. Instrumen ini memiliki peran yang signifikan dalam musik tradisional, terutama dalam ansambel gamelan di Indonesia. Gong terbuat dari logam seperti perunggu atau besi, dan suaranya dihasilkan dengan memukul bagian tengah atau tepi gong menggunakan pemukul khusus.</p>
            <p class="text-sm font-normal mt-2 font-semibold">Cara Memainkan</p>
            <p class="text-sm font-normal mt-2">Cara memainkan gong melibatkan pemukulan pada bagian tengah atau tepi gong dengan menggunakan alu atau pemukul khusus lainnya. Pemain gong harus memiliki kendali yang baik atas kekuatan pukulan untuk menghasilkan suara yang sesuai dengan konteks musik yang dimainkan. Gong sering dimainkan sebagai bagian dari ansambel gamelan, memberikan warna dan dinamika yang khas untuk keseluruhan komposisi.</p>
            <p class="text-sm font-normal mt-2 font-semibold">Sejarah</p>
            <p class="text-sm font-normal mt-2">Gong memiliki sejarah panjang dan mendalam, tidak hanya di Indonesia tetapi juga di berbagai budaya di Asia dan seluruh dunia. Di Indonesia, gong telah menjadi bagian integral dari musik tradisional, khususnya dalam ansambel gamelan yang mencakup berbagai instrumen perkusi dan melodis. Sejarah gong mencerminkan peran pentingnya dalam berbagai konteks, termasuk upacara adat, keagamaan, dan hiburan.</p>
            <p class="text-sm font-normal mt-2">
            Gong sering dihargai sebagai simbol keagungan dan kekuatan spiritual. Ukiran dan desain pada gong sering kali memiliki makna simbolis yang mendalam dan mencerminkan nilai-nilai budaya masyarakat tempatnya berasal. Meskipun gong masih digunakan dalam musik tradisional, instrumen ini juga telah diterima dalam konteks musik dunia dan digunakan dalam berbagai genre musik, menunjukkan fleksibilitas dan daya tarik universalnya.</p>
        </div>
        <div class="grid grid-cols-3 gap-2 w-full mb-24 block">
          <nuxt-link to="/materi/gendang" class="text-xs col-span-1 bg-main p-3 shadow-md rounded-3xl align-center text-center justify-center flex">
          <svg width="17" height="17" viewBox="0 0 24 24" data-name="Flat Color" xmlns="http://www.w3.org/2000/svg" class="mr-1 icon flat-color"><path d="M17.45 2.11a1 1 0 0 0-1.05.09l-12 9a1 1 0 0 0 0 1.6l12 9a1 1 0 0 0 1.05.09A1 1 0 0 0 18 21V3a1 1 0 0 0-.55-.89Z"/></svg>
                Gendang
          </nuxt-link>
          <div class="col-span-1">
          </div>
          <nuxt-link to="/materi/rebab" class="text-xs col-span-1 bg-main p-3 shadow-md rounded-3xl text-center justify-center flex leading-none tracking-tight">
          Rebab
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
