<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "@/components/HelloWorld.vue";
</script>

<template>
  <header>
    <div class="wrapper">
      <h1>RAHMAN ISLAM</h1>
      <h2>it support</h2>
      <nav>
        <RouterLink to="/">Tentang Saya</RouterLink>|
        <RouterLink to="/latar-belakang">Latar Belakang Pendidikan</RouterLink>|
        <RouterLink to="/protofolio">Protofolio</RouterLink>|
        <RouterLink to="/sertifikasi">Sertifikasi</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style>
/* @import "@/assets/base.css"; */
</style>
