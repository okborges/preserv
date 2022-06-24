<template>
  <main class="mb-96 bg-inicial px-5">
    <div class="pt-10 introducao max-w-6xl mx-auto">
      <div class="text-white grid grid-cols-2">
        <div class="self-end pb-48">
          <h1 class="pb-8 h1 poppins">
            <span class="solucoes poppins">SOLUÇÕES INTEGRADAS</span> DE
            <span class="text-azul-3 poppins">ENGENHARIA</span> E
            <span class="text-azul-3 poppins">CLIMATIZAÇÃO</span>
          </h1>
          <p class="pb-5 paragrafo text-cinza-claro">
            Inovação, sustentabilidade e tecnologia. Há mais de 30 anos
            entregando excelência e confiabilidade.
          </p>
          <a href="/" class="btn-inicial">ENTRE EM CONTATO</a>
        </div>
        <div>
          <img src="../static/img/img-1.webp" alt="" class="imagem" />
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style scoped>
.poppins {
  font-family: "Poppins", sans-serif;
}
.h1 {
  font-size: 4rem;
  line-height: 1.125;
}
.imagem {
  max-width: 100%;
  display: block;
}
.paragrafo {
  font-size: 1.5rem;
  line-height: 1.5;
}
.btn-inicial {
  display: inline-block;
  padding: 16px 32px;
  background: linear-gradient(#0ea5e9, #0c4a6e);
  border-radius: 4px;
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.1);
  font-size: 1.125rem;
  line-height: 1.33;
  font-weight: bold;
}
.btn-inicial:hover {
  background: linear-gradient(#0d7db1, #0a3d5a);
}

.introducao img {
  height: 100%;
  object-fit: cover;
  object-position: left;
  border-radius: 4px;
}
.bg-inicial {
  background-color: #222222;
  box-shadow: inset 0 -120px white;
}
</style>
