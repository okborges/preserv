<template>
  <div>
    <MainPincipal />
    <SectionUm />
    <SectionDois />
    <ParceirosClientes />
    <SobreNos />
  </div>
</template>

<script>
import SectionDois from "~/components/SectionDois.vue";
import ParceirosClientes from "~/components/ParceirosClientes.vue";
import SobreNos from "~/components/SobreNos.vue";
export default {
  name: "IndexPage",
  components: { SectionDois, ParceirosClientes, SobreNos },
};
</script>

<style>
* {
  font-family: "Poppins", sans-serif;
}
</style>
