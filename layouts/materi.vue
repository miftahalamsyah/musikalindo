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
                <nuxt-link to="/materi" class="text-sm font-bold flex text-earthy-brown">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" class="mr-1" fill="currentColor" viewBox="0 0 52 52" xml:space="preserve"><path d="M48.6 23H15.4c-.9 0-1.3-1.1-.7-1.7l9.6-9.6c.6-.6.6-1.5 0-2.1l-2.2-2.2c-.6-.6-1.5-.6-2.1 0L2.5 25c-.6.6-.6 1.5 0 2.1L20 44.6c.6.6 1.5.6 2.1 0l2.1-2.1c.6-.6.6-1.5 0-2.1l-9.6-9.6c-.6-.7-.2-1.8.7-1.8h33.2c.8 0 1.5-.6 1.5-1.4v-3c0-.8-.6-1.6-1.4-1.6z"/></svg>
                Kembali ke materi
                </nuxt-link>
                <div class="grid grid-cols-3">
                  <div class="col-span-3 sm:col-span-3 md:col-span-2 lg:col-span-2 h-screen">
                    <slot/>
                  </div>
                  <div class="grid col-span-1 mt-2 bg-white shadow-md rounded-3xl fixed hidden md:block lg:block" style="left: 65%; width: 20%;">
                      <nuxt-link to="/materi" class="text-sm text-neutral font-bold p-3 rounded-t-3xl flex hover:bg-stone-100">
                      Materi
                      </nuxt-link>
                      <nuxt-link to="/materi/mulut" class="text-sm text-neutral p-3 border-t-2 flex hover:bg-stone-100">
                      Mulut
                      </nuxt-link>
                      <nuxt-link to="/materi/esofagus" class="text-sm text-neutral p-3 border-t  flex hover:bg-stone-100">
                      Esofagus
                      </nuxt-link>
                      <nuxt-link to="/materi/lambung" class="text-sm text-neutral p-3 border-t  flex hover:bg-stone-100">
                      Lambung
                      </nuxt-link>
                      <nuxt-link to="/materi/usus-halus" class="text-sm text-neutral p-3 border-t flex hover:bg-stone-100">
                      Usus Halus
                      </nuxt-link>
                      <nuxt-link to="/materi/pankreas-dan-hati" class="text-sm text-neutral p-3 border-t flex hover:bg-stone-100">
                      Pankreas dan Hati
                      </nuxt-link>
                      <nuxt-link to="/materi/usus-besar" class="text-sm text-neutral p-3 border-t flex hover:bg-stone-100">
                      Usus Besar
                      </nuxt-link>
                      <nuxt-link to="/materi/rektum-dan-anus" class="text-sm text-neutral p-3 border-t rounded-b-3xl flex hover:bg-stone-100">
                      Rektum dan Anus
                      </nuxt-link>
                  </div>
                </div>
            </div>
        </section>
      </div>
    </body>
  </section>

  <footer class="footer items-center p-4 bg-base-100">
    <aside class="items-center grid-flow-col mx-auto">
      <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28"  fill="currentColor" viewBox="0 0 190.326 190.326" style="enable-background:new 0 0 190.326 190.326" xml:space="preserve"><path d="M60.776 87.985c-4.392-3.22-8.913-4.639-13.253-4.659-.091-7.059-.257-14.128-.365-21.196 2.333-1.73 4.597-3.489 6.703-5.334 11.432-10.009 18.963-24.581 17.818-40.008-.83-11.199-14.08-22.76-24.114-13.291-4.211 3.974-4.862 11.248-5.499 16.608-1.474 12.397-1.135 25.093-1.073 37.552.003.504.002 1.006.004 1.51-7.344 5.553-15.134 10.665-21.802 16.97C7.824 86.89.827 103.481 6.557 118.78c4.91 13.11 18.846 19.888 32.154 20.057.042 0 .085-.004.128-.004-.021.29-.036.578-.056.869-.631 8.783-.876 17.683.167 26.431-3.565-6.51-10.267-11.525-17.429-12.31-11.304-1.24-17.271 13.09-15.341 22.317 1.146 5.479 5.363 9.286 10.36 11.367 12.537 6.923 34.552.747 29.17-14.768-.057-.166-.159-.283-.237-.427-1.247-11.357-.977-22.71-.277-34.067 11.747-2.17 22.89-10.35 26.98-21.478 4.032-10.965-2.758-22.446-11.4-28.782zm-19.859-3.59c-7.499 2.494-13.824 9.112-17.006 17.505-1.191 3.139 4.042 5.342 5.426 2.288 2.582-5.697 5.997-11.094 11.494-13.45-.231 13.969-.718 27.908-1.592 41.937-.175.011-.353.03-.527.038-21.965.959-33.142-20.467-24.67-39.209 5.323-11.775 16.32-19.423 26.973-26.949.003 5.962-.031 11.906-.098 17.84zm7.422-64.289c.397-4.035 1.193-8.115 3.253-11.645 3.834-6.568 11.867 1.501 13.244 5.573 2.742 8.106-.702 19.043-5.018 26-3.457 5.573-7.891 10.141-12.75 14.278-.071-11.432.155-22.85 1.271-34.206zM45.645 131.55c.784-10.875 1.743-21.754 1.898-32.643.044-3.125.051-6.254.036-9.386 6.482.309 12.461 4.811 16.056 9.924 10.289 14.632-3.81 28.131-17.99 32.105zm138.434-57.8c.072-5.746 3.25-21.708-2.016-26.761.077-.771-.86-1.61-1.673-1.11-.016.009-.029.021-.044.031-.051-.013-.099-.037-.148-.05-.05-1.441-1.023-2.816-2.976-2.868-11.328-.304-23.998 4.394-34.737 7.437-6.606 1.872-13.199 3.891-19.58 6.437-2.432.97-6.995 2.343-8.573 4.993-.403.191-.754.486-.967.908-2.226 4.408-1.129 10.39-1.127 15.222.004 7.429.13 14.855.409 22.278.264 7.026.775 14.087 1.722 21.055.121.896.229 1.883.342 2.912-5.691-3.604-14.762-2.813-21.808 1.335-5.817 3.424-10.358 9.387-10.196 16.342.197 8.452 7.894 15.695 16.111 16.258 9.324.64 18.745-4.573 21.41-13.838.504-1.75.676-3.559.562-5.33.506-.055.967-.354 1.153-.943 1.46-4.6-.782-10.478-1.342-15.157-.9-7.524-1.368-15.064-1.693-22.634-.244-5.687-.318-11.379-.354-17.072 1.808-.552 3.601-1.472 5.035-2.037 6.831-2.691 13.643-5.432 20.499-8.058 9.677-3.706 22.521-10.244 33.136-9.831.404.016.8-.112 1.147-.33-.159 5.202-.676 10.453-.281 15.478 1.096 13.938 1.297 27.971 2.132 41.93-3.529-4.905-9.472-8.484-15.069-8.896-4.088-.301-7.807 1.474-10.823 4.138-11.339 3.862-14.262 23.294-3.333 30.817 2.546 1.753 5.447 2.676 8.442 2.923 4.512.947 9.434.576 13.402-.72 6.672-2.179 11.591-8.814 11.631-15.282.434-.338.76-.858.824-1.591 1.726-19.404-1.459-38.649-1.217-57.986zm-78.29 69.56c-.034.044-.073.074-.108.116 1.562-2.602 1.896-5.579-.356-7.156a3.32 3.32 0 0 0-.247-.544c.039-.017.079-.027.118-.044.075.061.156.113.228.177 1.102.967 1.576 2.304 1.661 3.705-.177 1.533-.751 3.067-1.296 3.746z"/></svg>
      <p>Musikalindo © 2023 - Belajar Alat Musik Indonesia</p>
    </aside> 
  </footer>
</template>
