<script setup>
import Header from '../components/Header/HeaderComp.vue'
import KongComp from '../components/Home/Kong/KongComp.vue';
import SeeComp from '../components/Home/See/SeeComp.vue';
import TheComp from '../components/Home/The/TheComp.vue';
import PastComp from '../components/Home/Past/PastComp.vue';
import StarComp from '../components/Home/Star/StarComp.vue';
import GameComp from '../components/Home/Game/GameComp.vue';
</script>

<template>
  <Header />
  <main>
    <SeeComp />
    <KongComp />
    <TheComp />
    <PastComp />
    <StarComp />
    <GameComp />
  </main>
</template>