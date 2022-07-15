<template>
  <section class="bg-claro pt-10 sm:pt-28" id="clientes">
    <h2 class="text-center text-3xl px-5 pb-10 sm:text-5xl lg:text-6xl sm:pb-0">
      Nossos parceiros<span class="text-azul-3">.</span>
    </h2>
    <div class="bg-branco px-5">
      <div class="conteiner">
        <div class="flex justify-center pb-20 pt-10 sm:pt-32">
          <img src="../static/img/parceiros.webp" alt="" />
        </div>
        <h2 class="text-center text-3xl sm:text-5xl lg:text-6xl px-5 pb-16">
          Nossos clientes<span class="text-azul-3">.</span>
        </h2>
        <div class="clientes pb-36">
          <img src="../static/img/safra-logo.webp" alt="" />
          <img src="../static/img/pacheco-logo.webp" alt="" />
          <img src="../static/img/pernambucanas-logo.webp" alt="" />
          <img src="../static/img/amaral-logo.svg" alt="" />
          <img src="../static/img/bsi-logo.webp" alt="" />
          <img src="../static/img/correio.webp" alt="" />
          <img src="../static/img/infraero-logo.webp" alt="" />
          <img src="../static/img/itau-logo.webp" alt="" />
          <img src="../static/img/petro-logo.webp" alt="" />
          <img src="../static/img/accor-log.webp" alt="" />
          <img src="../static/img/sym-logo.webp" alt="" />
          <img src="../static/img/cba-logo.webp" alt="" />
          <img src="../static/img/petropolis-logo.webp" alt="" />
          <img src="../static/img/blue-tree-logo.webp" alt="" />
          <img src="../static/img/poly-logo.webp" alt="" />
          <img src="../static/img/tivoli-logo.webp" alt="" />
          <img src="../static/img/pituka.webp" alt="" />
          <img src="../static/img/cosep-logo.webp" alt="" />
          <img src="../static/img/colegiosf-logo.webp" alt="" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.conteiner {
  max-width: 1300px;
  margin: auto;
}
.bg-claro {
  background-color: #fafafa;
}
.bg-branco {
  background-image: url(../static/bg-parceiros.svg);
  background-repeat: no-repeat;
  background-size: 100% 105%;
}
.clientes {
  display: flex;
  flex-wrap: wrap;
  gap: 50px;
  justify-content: center;
}
.clientes img {
  width: 120px;
}

@media (max-width: 768px) {
  .bg-branco {
    background-size: 200% 105%;
  }
}
@media (max-width: 639px) {
  .bg-branco {
    background-image: none;
    background-color: #ffffff;
  }
}
</style>
