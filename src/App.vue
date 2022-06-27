<script setup>
import HeaderComp from "@/components/HeaderComp.vue";
import MainComp from "@/components/MainComp.vue";
</script>

<template>
  <HeaderComp />
  <MainComp />
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: auto;
  margin: 0 auto;
  /* padding: 2rem; */
  height: 100vh;

  font-weight: normal;
}

</style>
