<template>
  <section class="bg-claro py-12 sm:py-24 px-5">
    <div class="sobre items-center max-w-6xl mx-auto">
      <h2 class="detalhe">SOBRE <span>NÓS</span></h2>
      <div>
        <h3 class="text-4xl text-preto-fosco pb-4">Nossos diferenciais</h3>
        <p class="text-xl text-cinza-escuro pb-10 max-w-xl">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Egestas urna
          ut aliquam eleifend nascetur. Ut massa diam sed sed amet.
        </p>
        <h3 class="text-4xl text-preto-fosco pb-4">Nossos valores</h3>
        <p class="text-xl text-cinza-escuro max-w-xl">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Egestas urna
          ut aliquam eleifend nascetur. Ut massa diam sed sed amet.
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.bg-claro {
  background-color: #fafafa;
}
.detalhe {
  color: #0ea5e9;
  font-size: 7.813rem;
  max-width: 5ch;
  font-weight: bold;
  line-height: 200px;
}
.detalhe span {
  font-size: 11.8rem;
}
.sobre {
  display: grid;
  grid-template-columns: 1fr 1fr;
}

@media (max-width: 900px) {
  .sobre {
    grid-template-columns: 1fr;
    gap: 30px;
  }
  .detalhe {
    font-size: 7rem;
    max-width: 20ch;
    line-height: 130px;
  }
  .detalhe span {
    font-size: 7rem;
  }
}
@media (max-width: 640px) {
  .detalhe {
    font-size: 3.7rem;
    max-width: 20ch;
  }
  .detalhe span {
    font-size: 3.7rem;
  }
}
</style>
