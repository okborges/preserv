<template>
  <section class="bg-carousel">
    <div class="max-w-6xl mx-auto mt-8 sm:mt-24">
      <div class="flex justify-between items-center py-8">
        <div>
          <h1 class="titulo text-6xl font-bold">
            <span class="solucao">SOLUÇÕES INTEGRADAS</span><br />DE
            ENGENHARIA<br />E CLIMATIZAÇÃO
          </h1>
          <p class="text-xl font-semibold mt-8 cor-5">
            Inovação, sustentabilidade e tecnologia.<br />
            Há mais de 30 anos entregando excelência<br />
            e confiabilidade.
          </p>
        </div>
        <div class="text-center items-center flex flex-col gap-10">
          <h2 class="text-3xl font-bold cor-5">
            OBTENHA CONSULTORIA<br />
            DO SEU PROJETO AQUI
          </h2>
          <button class="btn-contato font-bold">Entre em contato</button>
          <P class="text-2xl font-bold cor-5">Resposta em até 24h!</P>
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
  background-image: url(/img/img1.webp);
  transition: 3s;

  animation-name: fade;
  animation-direction: alternate-reverse;
  animation-play-state: running;
  animation-duration: 40s;
  animation-fill-mode: forwards;
  animation-iteration-count: infinite;
}
@keyframes fade {
  25% {
    background-image: url(/img/img2.webp);
  }
  50% {
    background-image: url(/img/img3.webp);
  }
  75% {
    background-image: url(/img/img4.webp);
  }
  100% {
    background-image: url(/img/img5.webp);
  }
}
.cor-4 {
  color: #006490;
}
.cor-5 {
  color: #0c4a6e;
}

.btn-contato {
  width: 169px;
  height: 62px;
  background-color: #e0f2fe;
  color: #0369aa;
  border-radius: 6px;
}
</style>
