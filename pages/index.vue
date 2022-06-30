<template>
  <div>
    <MainPincipal />
    <SectionUm />
    <SectionDois />
  </div>
</template>

<script>
import SectionDois from "~/components/SectionDois.vue";
export default {
  name: "IndexPage",
  components: { SectionDois },
};
</script>

<style>
* {
  font-family: "Poppins", sans-serif;
}
</style>
