<template>
  <section class="bg-clarinho px-5 pb-24">
    <div class="max-w-6xl mx-auto">
      <h2 class="h2">Por que escolher a Preserv?</h2>
      <div class="grid justify-center gap-10 lg:grid-cols-3">
        <div class="card text-center py-5">
          <a @click="showModal = true">
            <div class="pb-8">
              <img src="../static/icone-card-1.svg" alt="" class="inline" />
            </div>
            <h3 class="pb-2 text-lg font-semibold text-preto-fosco">
              Seguimos normas técnicas
            </h3>
            <p class="p-2 text-cinza-escuro">
              Em todo e qualquer procedimento de instalação e manutenção
              cumprimos padrões e normas, do início ao fim, para o conforto e
              segurança de todos os nossos clientes!
            </p>
          </a>
          <SavedModal v-show="showModal" @close-modal="showModal = false" />
        </div>
        <div class="card text-center py-5">
          <a href="/">
            <div class="pb-8">
              <img src="../static/icone-card-2.svg" alt="" class="inline" />
            </div>
            <h3 class="pb-2 text-lg font-semibold text-preto-fosco">
              Somos sustentáveis
            </h3>
            <p class="p-2 text-cinza-escuro">
              Atendemos todas as instruções normativas do IBAMA (Instituto
              Brasileiro do Meio Ambiente e dos Recursos Naturais Renováveis) e
              <br />
              CONAMA.
            </p>
          </a>
        </div>
        <div class="card text-center py-5">
          <a href="/">
            <div class="pb-8">
              <img src="../static/icone-card-3.svg" alt="" class="inline" />
            </div>
            <h3 class="pb-2 text-lg font-semibold text-preto-fosco">
              Experiência Certificada
            </h3>
            <p class="p-2 text-cinza-escuro">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Lacus
              pellentesque quisque tincidunt amet, volutpat. Viverra
              pellentesque faucibus vitae aliquam, dignissim.
            </p>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
import SavedModal from "~/components/SavedModal.vue";

export default {
  components: { SavedModal },
  data() {
    return {
      showModal: false,
    };
  },
};
</script>

<style scoped>
.bg-clarinho {
  background-color: #fafafa;
}
.card {
  display: grid;
  justify-items: center;
  width: 100%;
  height: auto;

  background: #ffffff;
  border: 2px solid #0ea5e9;
  border-radius: 18px;
}
.card:hover {
  cursor: pointer;
  box-shadow: 0px 0px 0px 6px #83d9ff;
  transition: 0.2s;
}
.h2 {
  text-align: center;
  font-size: 3.75rem;
  padding-bottom: 4rem;
  color: #222222;
}

@media (max-width: 1024px) {
  .card {
    width: 60%;
    height: auto;
    margin: auto;
  }
}
@media (max-width: 640px) {
  .card {
    width: 100%;
    height: auto;
    margin: auto;
  }
  .h2 {
    font-size: 1.875rem;
    line-height: 2.6rem;
    padding-bottom: 2.5rem;
  }
}
</style>
