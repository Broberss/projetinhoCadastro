<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <nav>
    <RouterLink to="/home">Home</RouterLink>
    <RouterLink to="/jogadores">Jogadores</RouterLink>
    <RouterLink to="/times">Times</RouterLink>
    <RouterView></RouterView>
  </nav>
  <footer></footer>
</template>
