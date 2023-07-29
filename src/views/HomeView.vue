<script setup>
import Header from '../components/Header/HeaderComp.vue'
import KongComp from '../components/Home/Kong/KongComp.vue';
import SeeComp from '../components/Home/See/SeeComp.vue';
import TheComp from '../components/Home/The/TheComp.vue';
import PastComp from '../components/Home/Past/PastComp.vue';
</script>

<template>
  <main>
    <Header />
    <SeeComp />
    <KongComp />
    <TheComp />
    <PastComp />
  </main>
</template>