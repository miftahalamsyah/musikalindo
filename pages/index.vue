<template>
  <head>
    <title>Musikalindo</title>
  </head>

  <section class="max-w-6xl justify-center mx-auto px-5 mb-24">
    <div class="hero min-h-screen">
      <div class="hero-content flex-col lg:flex-row">
        <img src="~/public/angklung.png" class="max-w-sm shaky-image hidden sm:hidden md:block lg:block" />
        <div>
          <h1 class="text-2xl md:text-3xl lg:text-4xl font-bold">Eksplorasi Alat Musik Tradisional</h1>
          <p class="py-6 text-lg">Selamat datang di Musikalindo! Sumber pembelajaran alat musik tradisional Indonesia. Dengan materi edukatif kami, dengan hadiri kelas virtual menggunakan teknologi Realitas Virtual (VR) untuk pengalaman belajar yang lebih menarik. Bergabunglah dengan kami di Musikalindo dan temukan keindahan melodi tradisional Indonesia!</p>
          <nuxt-link to="materi" class="bg-main rounded-2xl text-sm p-3 font-bold">Mulai Sekarang!</nuxt-link>
        </div>
      </div>
    </div>

    <div class="my-5 p-5 card rounded-box place-items-center font-extrabold">
      Konten
    </div>
    <div class="grid grid-cols-1 sm:grid-cols-1 lg:grid-cols-3 gap-4 w-full gap-2 mb-24">
      <nuxt-link to="/materi" class="group grid card bg-base-300 rounded-box place-items-center relative overflow-hidden transition duration-300 transform hover:scale-110">
        <img src="~/public/covermateri.jpg" class="relative mb-2 max-h-36 object-cover w-full " />
        <h1 class="text-xl md:text-2xl lg:text-2xl font-semibold px-5 py-2">Materi</h1>
        <p class="px-5 pb-12 text-sm">Eksplorasi mengenai alat musik tradisional Indonesia, merangkum sejarah, teknik bermain, dan keunikan warisan Nusantara.</p>
      </nuxt-link>
      <nuxt-link to="/kuis" class="group grid card bg-base-300 rounded-box place-items-center relative overflow-hidden transition duration-300 transform hover:scale-110">
        <img src="~/public/coverkuis.jpg" class="relative mb-2 max-h-36 object-cover w-full " />
        <h1 class="text-xl md:text-2xl lg:text-2xl font-semibold px-5 py-2">Kuis</h1>
        <p class="px-5 pb-12 text-sm">Memberikan kesempatan bagi pengguna untuk menguji dan meningkatkan pengetahuan mereka tentang alat musik tradisional Indonesia dengan cara yang menyenangkan.</p>
      </nuxt-link>
      <nuxt-link to="/hubs" class="group grid card bg-base-300 rounded-box place-items-center relative overflow-hidden transition duration-300 transform hover:scale-110">
        <img src="~/public/hubslobby.png" class="relative mb-2 max-h-36 object-cover w-full " />
        <h1 class="text-lg md:text-xl lg:text-xl font-semibold px-5 py-2">Hubs</h1>
        <p class="px-5 pb-12 text-sm">Pengalaman belajar menjadi lebih imersif dengan teknologi Realitas Virtual (VR) melalui Mozilla Hubs, musik tradisional Indonesia dalam lingkungan virtual yang interaktif.</p>
      </nuxt-link>
    </div>

  </section>
</template>

<script setup>
</script>
<style scoped>
.shaky-image {
  animation: swing 3s ease-in-out infinite; /* Adjust the duration and easing as needed */
  transform-origin: center top; /* Set the transform origin to the bottom center for swinging effect */
}

@keyframes swing {
  0% { transform: rotate(0deg); }
  50% { transform: rotate(10deg); }
  100% { transform: rotate(0deg); }
}
</style>
