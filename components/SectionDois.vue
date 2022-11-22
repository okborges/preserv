<template>
  <section class="px-5 pb-24 max-w-6xl mx-auto">
    <p class="text-azul-800 text-center font-semibold">NOSSOS DIFERENCIAIS</p>
    <h2
      class="text-center text-azul-1000 font-semibold mb-16 text-4xl lg:text-6xl"
    >
      Por que a Preserv é uma<br class="hidden lg:block" />
      referência no mercado?
    </h2>

    <div class="grid gap-10 lg:grid-cols-3">
      <div class="card text-center">
        <img src="~/assets/icon/icon-card-1.svg" alt="" />
        <h3 class="text-lg font-semibold">Seguimos normas técnicas</h3>
        <p>
          Em todo e qualquer procedimento de instalação e manutenção cumprimos
          padrões e normas, do início ao fim, para o conforto e segurança de
          todos os nossos clientes!
        </p>

        <SavedModal v-show="showModal" @close-modal="showModal = false" />
      </div>

      <div class="card text-center">
        <img src="~/assets/icon/icon-card-2.svg" alt="" />
        <h3 class="text-lg font-semibold">Somos sustentáveis</h3>
        <p>
          Atendemos todas as instruções normativas do IBAMA (Instituto
          Brasileiro do Meio Ambiente e dos Recursos Naturais Renováveis) e
          CONAMA.
        </p>
      </div>

      <div class="card text-center">
        <img src="~/assets/icon/icon-card-3.svg" alt="" />
        <h3 class="text-lg font-semibold">Experiência Certificada</h3>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Lacus
          pellentesque quisque tincidunt amet, volutpat. Viverra pellentesque
          faucibus vitae aliquam, dignissim.
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
section {
  h2 {
    line-height: 75px;
  }
  .card {
    display: grid;
    padding: 30px;
    justify-items: center;
    width: 100%;
    height: auto;
    gap: 10px;

    background: #ffffff;
    border: 2px solid #0ea5e9;
    border-radius: 18px;
    filter: drop-shadow(0px 7.36842px 9.21053px rgba(0, 0, 0, 0.25));

    p {
      font-size: 14px;
    }
  }
  .card:hover {
    cursor: pointer;
    box-shadow: 0px 0px 0px 6px #14668e;
    transition: 0.2s;
  }

  @media (max-width: 1024px) {
    h2 {
      line-height: 50px;
    }
  }
}
</style>
