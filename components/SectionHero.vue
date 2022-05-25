<template>
  <section class="bg-carousel">
    <div class="max-w-6xl mx-auto mt-8 sm:mt-24">
      <div class="flex justify-between items-center">
        <div>
          <h1 class="titulo text-6xl font-bold">
            <span class="solucao">SOLUÇÕES INTEGRADAS</span><br />DE
            ENGENHARIA<br />E CLIMATIZAÇÃO
          </h1>
          <p class="text-xl font-semibold mt-8">
            Inovação, sustentabilidade e tecnologia.<br />
            Há mais de 30 anos entregando excelência<br />
            e confiabilidade.
          </p>
        </div>
        <div class="text-center flex flex-col gap-8">
          <h2 class="text-3xl font-bold">
            OBTENHA CONSULTORIA<br />
            DO SEU PROJETO AQUI
          </h2>
          <button>Entre em contato</button>
          <P class="text-2xl font-bold">Resposta em até 24h!</P>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.titulo {
  color: #0369a1;
  line-height: 4.375rem;
}

.solucao {
  font-size: 2.563rem;
}

.bg-carousel {
  width: 100%;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  background-image: url(/img/img4.webp);
  transition: 5s;
}
</style>
