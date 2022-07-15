<template>
  <main class="pb-24 bg-inicial px-5">
    <div class="introducao max-w-6xl mx-auto">
      <div class="text-white grid lg:grid-cols-2">
        <div class="max-w-lg pb-8 pt-8 lg:pt-24 mx-auto lg:mx-0">
          <h1 class="pb-7 titulo">
            <span class="solucoes">SOLUÇÕES INTEGRADAS</span>
            <span class="engenharia"
              >DE <span class="detalhe">ENGENHARIA</span></span
            >
            E
            <span class="detalhe">CLIMATIZAÇÃO</span>
          </h1>
          <p class="pb-9 paragrafo text-cinza-claro">
            Inovação, sustentabilidade e tecnologia.<br />
            Há mais de <span class="detalhe">30 anos</span> entregando
            excelência<br />
            e confiabilidade.
          </p>
          <div class="text-center">
            <a href="/contato" class="btn-inicial mb-4">ENTRE EM CONTATO</a>
            <span class="text-azul-5 block">Retorno em até 24h!</span>
          </div>
        </div>
        <div class="flex lg:justify-end">
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
  font-size: 3.8rem;
  line-height: 1.2;
  font-weight: 600;
  max-width: 20ch;
}
.solucoes {
  font-size: 2.7rem;
}
.engenharia {
  font-size: 4rem;
}
.paragrafo {
  font-size: 1.4rem;
  line-height: 1.5;
}
.detalhe {
  color: #0ea5e9;
}
.imagem {
  max-width: 91%;
  display: block;
}
.btn-inicial {
  display: inline-block;
  padding: 16px 32px;
  background: linear-gradient(#0ea5e9, #0c4a6e);
  border-radius: 4px;
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.1);
  font-size: 1.125rem;
  line-height: 1.33;
  font-weight: 600;
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
  box-shadow: inset 0 -120px #fafafa, inset 0 25px #fafafa;
}

@media (max-width: 1060px) {
  .titulo {
    font-size: 3.6rem;
    max-width: 13ch;
  }
  .solucoes {
    font-size: 2.55rem;
  }
  .engenharia {
    font-size: 3.8rem;
  }
}
@media (max-width: 1024px) {
  .introducao img {
    height: 300px;
    width: 100%;
    object-position: bottom;
  }
  .btn-inicial {
    padding: 12px 24px;
    font-size: 1.1rem;
    line-height: 1.33;
  }
  .imagem {
    max-width: 100%;
  }
}
@media (max-width: 640px) {
  .titulo {
    font-size: 2.4rem;
    max-width: 13ch;
  }
  .solucoes {
    font-size: 1.7rem;
  }
  .engenharia {
    font-size: 2.5rem;
  }
  .paragrafo {
    max-width: 340px;
    font-size: 1rem;
    line-height: 1.5;
  }
  .paragrafo br {
    display: none;
  }
}
</style>
