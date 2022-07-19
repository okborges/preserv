<template>
  <div>
    <MainPincipal />
    <ServicosPrestados />
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
import ServicosPrestados from "~/components/ServicosPrestados.vue";
export default {
  name: "IndexPage",
  components: {
    SectionDois,
    ParceirosClientes,
    SobreNos,
    NossoContato,
    ServicosPrestados,
  },
};
</script>

<style>
* {
  font-family: "Poppins", sans-serif;
}
</style>
