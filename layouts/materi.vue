<script setup>
</script>

<template>
  <section>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <body style="font-family: 'Poppins', sans-serif;">
      <Sidebar/>
      <div class=" max-w-5xl mx-auto mt-24 px-4 text-2xl text-primary-content min-h-screen">
        <section class="mt-8 max-w-6xl justify-center mx-auto px-5">
            <div class="w-full">
                <nuxt-link to="/materi" class="text-sm font-bold flex text-base-content">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" class="mr-1" fill="currentColor" viewBox="0 0 52 52" xml:space="preserve"><path d="M48.6 23H15.4c-.9 0-1.3-1.1-.7-1.7l9.6-9.6c.6-.6.6-1.5 0-2.1l-2.2-2.2c-.6-.6-1.5-.6-2.1 0L2.5 25c-.6.6-.6 1.5 0 2.1L20 44.6c.6.6 1.5.6 2.1 0l2.1-2.1c.6-.6.6-1.5 0-2.1l-9.6-9.6c-.6-.7-.2-1.8.7-1.8h33.2c.8 0 1.5-.6 1.5-1.4v-3c0-.8-.6-1.6-1.4-1.6z"/></svg>
                Kembali ke materi
                </nuxt-link>
                <div class="grid grid-cols-3">
                  <div class="col-span-3 sm:col-span-3 md:col-span-2 lg:col-span-2 h-screen">
                    <slot/>
                  </div>
                  <div class="grid col-span-1 mt-2 bg-base-300 text-base-content shadow-md rounded-3xl fixed hidden md:block lg:block" style="left: 65%; width: 20%;">
                      <nuxt-link to="/materi/angklung" class="text-sm p-3 border-t-2 border-base-100 rouned-t-3xl flex hover:bg-base-200">
                      Angklung
                      </nuxt-link>
                      <nuxt-link to="/materi/bonang" class="text-sm p-3 border-t  border-base-100 flex hover:bg-base-200">
                      Bonang
                      </nuxt-link>
                      <nuxt-link to="/materi/gendang" class="text-sm p-3 border-t  border-base-100 flex hover:bg-base-200">
                      Gendang
                      </nuxt-link>
                      <nuxt-link to="/materi/gong" class="text-sm p-3 border-t border-base-100 flex hover:bg-base-200">
                      Gong
                      </nuxt-link>
                      <nuxt-link to="/materi/rebab" class="text-sm p-3 border-t border-base-100 flex hover:bg-base-200">
                      Rebab
                      </nuxt-link>
                      <nuxt-link to="/materi/sapek" class="text-sm p-3 border-t border-base-100 flex hover:bg-base-200">
                      Sapek
                      </nuxt-link>
                      <nuxt-link to="/materi/saron" class="text-sm p-3 border-t border-base-100 flex hover:bg-base-200">
                      Saron
                      </nuxt-link>
                      <nuxt-link to="/materi/serunai" class="text-sm p-3 border-t border-base-100 rounded-b-3xl flex hover:bg-base-200">
                      Serunai
                      </nuxt-link>
                  </div>
                </div>
            </div>
        </section>
      </div>
    </body>
  </section>
</template>
