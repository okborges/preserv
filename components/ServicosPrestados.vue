<template>
  <section class="bg-preto-fosco px-5" id="servicos">
    <h1 class="text-6xl font-medium text-center text-white py-20">
      Serviços<span class="text-azul-3">.</span>
    </h1>
    <ServicoUm />
    <ServicosDois />
    <ServicosTres />
  </section>
</template>

<script>
import ServicoUm from "./ServicoUm.vue";
import ServicosDois from "./ServicosDois.vue";
import ServicosTres from "./ServicosTres.vue";
export default { components: { ServicoUm, ServicosDois, ServicosTres } };
</script>

<style scoped></style>
