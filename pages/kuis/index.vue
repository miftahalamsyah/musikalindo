<template>
  <head>
    <title>Kuis | Musikalindo</title>
  </head>
  <section class="mt-8 max-w-6xl justify-center mx-auto px-5">
    <div class="py-12 px-4 mx-auto text-center z-20 animate-up">
      <h1 class="text-xl font-extrabold tracking-tight leading-none md:text-2xl lg:text-3xl">Kuis</h1>
      <p class="text-sm">Uji Pengetahuan Anda Melalui Kuis Berikut</p>
    </div>
    <div class="mb-48">
      <div class="w-full bg-white border border-gray-200 rounded-3xl shadow-md relative">
        <iframe
          src="https://evaluasiarrarayuk.vercel.app/"
          id="fullscreenIframe"
          class="rounded-2xl h-screen shadow-md border border-gray-100"
          frameborder="0"
          width="100%"
          height="100%"
        ></iframe>
        <button @click="toggleFullscreen" class="absolute top-4 right-4 bg-main text-stone-50 text-sm px-3 py-1 rounded-3xl">
          Fullscreen
        </button>
      </div>
    </div>
  </section>
</template>

<script setup>
const toggleFullscreen = () => {
  const iframe = document.getElementById('fullscreenIframe');

  if (!document.fullscreenElement) {
    iframe.requestFullscreen().catch((err) => {
      console.error(`Error attempting to enable fullscreen: ${err.message}`);
    });
  } else {
    document.exitFullscreen();
  }
};
</script>

<style scoped>
</style>
