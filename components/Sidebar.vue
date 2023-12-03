<template>
<div class="navbar fixed top-0 bg-base-100 z-20">
  <div class="navbar-start">
    <div class="dropdown">
      <div tabindex="0" role="button" class="btn btn-ghost btn-circle">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h7" /></svg>
      </div>
      <ul tabindex="0" class="menu menu-sm dropdown-content mt-3 z-[1] p-2 shadow bg-base-100 rounded-box w-52">
        <li><nuxt-link to="/">Beranda</nuxt-link></li>
        <li><nuxt-link to="/materi">Materi</nuxt-link></li>
        <li><nuxt-link to="/kuis">Kuis</nuxt-link></li>
        <li><nuxt-link to="/hubs">Hubs</nuxt-link></li>
      </ul>
    </div>
  </div>
  <div class="navbar-center">
    <nuxt-link to="/" class="btn btn-ghost text-xl logo">Musikalindo</nuxt-link>
  </div>
  <div class="navbar-end">
  </div>
</div>
</template>

<script setup>
</script>
