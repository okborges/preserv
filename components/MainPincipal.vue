<template>
  <main class="mx-8">
    <SectionHero />
    <SectionCards />
    <AboutUs />
  </main>
</template>

<script>
import SectionCards from "./SectionCards.vue";
import SectionHero from "./SectionHero.vue";
import AboutUs from "./AboutUs.vue";
export default { components: { SectionCards, SectionHero, AboutUs } };
</script>

<style scoped></style>
