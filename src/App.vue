<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "@/components/HelloWorld.vue";
</script>

<template>
  <header>
    <div class="wrapper">
      <div class="navbar">
        <h1>RAHMAN ISLAM</h1>
        <h2>it support</h2>
        <ul>
          <li><RouterLink to="/" class="active">Tentang Saya</RouterLink></li>
          <li>
            <RouterLink to="/latar-belakang"
              >Latar Belakang Pendidikan</RouterLink
            >
          </li>
          <li><RouterLink to="/protofolio">Protofolio</RouterLink></li>
          <li><RouterLink to="/sertifikasi">Sertifikasi</RouterLink></li>
        </ul>
      </div>
    </div>
  </header>

  <RouterView />
</template>

<style>
/* @import "@/assets/base.css"; */
@import "@/assets/custom.css";
</style>
