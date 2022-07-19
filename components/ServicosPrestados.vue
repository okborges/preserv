<template>
  <section class="bg-preto-fosco px-5">
    <h1 class="text-6xl font-medium text-center text-white py-20">
      Serviços<span class="text-azul-3">.</span>
    </h1>
    <ServicoUm />
  </section>
</template>

<script>
import ServicoUm from "./ServicoUm.vue";
export default { components: { ServicoUm } };
</script>

<style scoped></style>
