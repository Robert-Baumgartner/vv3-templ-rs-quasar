<script setup>
import {  RouterView } from 'vue-router';
</script>

<template>
  <div class="text-center">

    <q-tabs class="bg-green-10 text-white q-my-md q-py-sm" dense  indicator-color="yellow-5">
      <q-route-tab to="/" icon="home" label="Home" />
      <q-route-tab to="/about" icon="info" label="About" />
    </q-tabs>

    <div class="d-flex justify-content-center"><RouterView /></div>
  </div>
</template>
