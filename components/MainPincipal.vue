<template>
  <main class="mb-96 bg-inicial px-5">
    <div class="pt-10 introducao max-w-6xl mx-auto">
      <div class="text-white grid grid-cols-2">
        <div class="self-end pb-48 max-w-lg">
          <h1 class="pb-8 titulo">
            <span class="solucoes">SOLUÇÕES INTEGRADAS</span>
            <span class="engenharia"
              >DE <span class="detalhe">ENGENHARIA</span></span
            >
            E
            <span class="detalhe">CLIMATIZAÇÃO</span>
          </h1>
          <p class="pb-5 paragrafo text-cinza-claro">
            Inovação, sustentabilidade e tecnologia.<br />
            Há mais de <span class="detalhe">30 anos</span> entregando
            excelência<br />
            e confiabilidade.
          </p>
          <a href="/" class="btn-inicial">ENTRE EM CONTATO</a>
        </div>
        <div class="flex justify-end">
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
.titulo {
  font-size: 3.65rem;
  line-height: 1.125;
  font-weight: 600;
  max-width: 20ch;
}
.solucoes {
  font-size: 2.6rem;
}
.engenharia {
  font-size: 3.84rem;
}
.detalhe {
  color: #0ea5e9;
}
.imagem {
  max-width: 100%;
  display: block;
}
.paragrafo {
  font-size: 1.4rem;
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

.gambiarra {
  font-size: 94%;
}
</style>
