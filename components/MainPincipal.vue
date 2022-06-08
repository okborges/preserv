<template>
  <main class="mx-8">
    <SectionHero />
    <SectionCards />
    <AboutUs />
    <NossosParceiros />
  </main>
</template>

<script>
import SectionCards from "./SectionCards.vue";
import SectionHero from "./SectionHero.vue";
import AboutUs from "./AboutUs.vue";
import NossosParceiros from "./NossosParceiros.vue";
export default {
  components: { SectionCards, SectionHero, AboutUs, NossosParceiros },
};
</script>

<style scoped></style>
