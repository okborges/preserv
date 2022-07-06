<template>
  <div>
    <MainPincipal />
    <SectionUm />
    <SectionDois />
    <ParceirosClientes />
  </div>
</template>

<script>
import SectionDois from "~/components/SectionDois.vue";
import ParceirosClientes from "~/components/ParceirosClientes.vue";
export default {
  name: "IndexPage",
  components: { SectionDois, ParceirosClientes },
};
</script>

<style>
* {
  font-family: "Poppins", sans-serif;
}
</style>
