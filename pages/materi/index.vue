<template>
    <head>
      <title>Materi | Musikalindo</title>
    </head>
    <section class="mt-8 max-w-6xl justify-center mx-auto px-5">
      <div class="py-8 px-4 mx-auto text-center z-20 animate-up">
        <h1 class="text-xl font-extrabold tracking-tight leading-none md:text-2xl lg:text-3xl">Materi Pembelajaran</h1>
        <p class="text-sm">Koleksi materi pembelajaran</p>
      </div>
      <div class="grid grid-cols-1 sm:grid-cols-1 lg:grid-cols-3 gap-4 mb-24">
        <nuxt-link to="/materi/angklung" class="text-sm bg-main text-stone-50 p-5 shadow-md rounded-3xl flex font-bold">
          Angklung
        </nuxt-link>
        <nuxt-link to="/materi/bonang" class="text-sm bg-main text-stone-50 p-5 shadow-md rounded-3xl flex font-bold">
          Bonang
        </nuxt-link>
        <nuxt-link to="/materi/gendang" class="text-sm bg-main text-stone-50 p-5 shadow-md rounded-3xl flex font-bold">
          Gendang
        </nuxt-link>
        <nuxt-link to="/materi/gong" class="text-sm bg-main text-stone-50 p-5 shadow-md rounded-3xl flex font-bold">
          Gong
        </nuxt-link>
        <nuxt-link to="/materi/rebab" class="text-sm bg-main text-stone-50 p-5 shadow-md rounded-3xl flex font-bold">
          Rebab
        </nuxt-link>
        <nuxt-link to="/materi/sapek" class="text-sm bg-main text-stone-50 p-5 shadow-md rounded-3xl flex font-bold">
          Sapek
        </nuxt-link>
        <nuxt-link to="/materi/saron" class="text-sm bg-main text-stone-50 p-5 shadow-md rounded-3xl flex font-bold">
          Saron
        </nuxt-link>
        <nuxt-link to="/materi/serunai" class="text-sm bg-main text-stone-50 p-5 shadow-md rounded-3xl flex font-bold">
          Serunai
        </nuxt-link>
      </div>
      <hr class="border-t border-neutral flex-grow pb-8">
      <div class="px-4 mx-auto text-center z-20 animate-up">
        <p class="text-xl font-bold">Kuis</p>
      </div>
      <nuxt-link to="/kuis" class="mt-3 mb-24 w-full inline-flex items-center p-5 text-sm font-medium text-center text-secondary-content bg-second shadow-md rounded-3xl">
        Kuis
        <svg class="w-3.5 h-3.5 ml-2" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
            <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 5h12m0 0L9 1m4 4L9 9"/>
        </svg>
      </nuxt-link>
    </section>
  </template>
  
  <script setup>
  </script>
  <style scoped>
  </style>
  
