<template>
  <div>
    <MainPincipal />
    <SectionUm />
    <SectionDois />
    <ParceirosClientes />
    <SobreNos />
    <NossoContato />
  </div>
</template>

<script>
import SectionDois from "~/components/SectionDois.vue";
import ParceirosClientes from "~/components/ParceirosClientes.vue";
import SobreNos from "~/components/SobreNos.vue";
import NossoContato from "~/components/NossoContato.vue";
export default {
  name: "IndexPage",
  components: { SectionDois, ParceirosClientes, SobreNos, NossoContato },
};
</script>

<style>
* {
  font-family: "Poppins", sans-serif;
}
</style>
