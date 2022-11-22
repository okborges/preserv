<template>
  <section class="px-5 bg-cinza-900 mb-16">
    <div class="text-white max-w-6xl mx-auto grid lg:grid-cols-2">
      <div class="self-center py-8 mt-4 lg:mx-0 lg:mt-0">
        <h1 class="pb-7 text-center mx-auto lg:mx-0 lg:text-left">
          SOLUÇÕES INTEGRADAS DE ENGENHARIA E CLIMATIZAÇÃO
        </h1>
        <p class="pb-9 text-xl text-center lg:text-left">
          Inovação, sustentabilidade e tecnologia.<br />
          Há mais de <span class="text-azul-500">30 anos</span> entregando
          excelência e confiabilidade.
        </p>
        <div class="text-center">
          <a href="/#contato" class="mb-4">ENTRE EM CONTATO</a>
          <span class="block">Retorno em até 24h!</span>
        </div>
      </div>
      <div class="flex px-3 lg:justify-end">
        <img src="~/assets/img/img-1.webp" alt="" />
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
section {
  box-shadow: inset 0 -25px #eef0f5, inset 0 25px #eef0f5;

  h1 {
    font-size: 40px;
    line-height: 1.2;
    font-weight: 600;
    max-width: 20ch;
  }

  img {
    height: 650px;
    display: block;
    object-fit: cover;
    object-position: left;
    filter: drop-shadow(0px 7.36842px 9.21053px rgba(0, 0, 0, 0.25));
    border-radius: 0.25rem;
  }

  a {
    display: inline-block;
    padding: 16px 32px;
    border-radius: 4px;
    box-shadow: 0 1px 2px rgba(0, 0, 0, 0.1);
    font-size: 1.125rem;
    line-height: 1.33;
    font-weight: 600;
    background: linear-gradient(#0ea5e9, #0e5680);
  }
  a:hover {
    background: linear-gradient(#0d7db1, #0a3d5a);
  }

  @media (max-width: 991px) {
    h1 {
      font-size: 35px;
    }
    img {
      height: 200px;
      width: 100%;
      object-position: bottom;
    }

    a {
      padding: 12px 24px;
      font-size: 1.1rem;
      line-height: 1.33;
    }
  }
}
</style>
