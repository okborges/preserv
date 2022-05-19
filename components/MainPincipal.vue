<template>
  <main class="mx-8">
    <SectionHero />
    <SectionCards />
  </main>
</template>

<script>
import SectionCards from "./SectionCards.vue";
import SectionHero from "./SectionHero.vue";
export default { components: { SectionCards, SectionHero } };
</script>

<style scoped></style>
