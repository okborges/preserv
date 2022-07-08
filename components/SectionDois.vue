<template>
  <section class="bg-inicial px-5">
    <div class="max-w-6xl mx-auto">
      <div class="grid lg:grid-cols-2 gap-5">
        <div class="imagem hidden lg:block">
          <img class="rounded" src="../static/img/img-2.webp" alt="" />
        </div>
        <div class="py-10 lg:pt-28 lg:pl-5">
          <h2 class="titulo pb-9">
            Benefícios de um<br />
            <span class="text-azul-3">Ambiente Climatizado</span>.
          </h2>
          <p class="text-cinza-claro text-xl pb-7 paragrafo">
            O ar-condicionado é considerado um item indispensável para todos os
            tipos de ambientes e já deixou de ser um item de luxo para se tornar
            um item necessário em diversos locais.
          </p>
          <a href="" class="saiba">SAIBA MAIS</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.bg-inicial {
  background-color: #222222;
  box-shadow: inset 0 -30px #fafafa, inset 0 30px #fafafa;
}
.titulo {
  color: #ffffff;
  font-size: 3.2rem;
  font-weight: 700;
  line-height: 145%;
}
.titulo span {
  font-size: 4rem;
}
.saiba {
  display: inline-block;
  color: #0ea5e9;
  font-size: 1.5rem;
  font-weight: 700;
  letter-spacing: 0.05em;
  position: relative;
}
.saiba::after {
  content: "";
  display: block;
  width: 100%;
  height: 3px;
  background-color: #0ea5e9;
  margin-top: 4px;
}
.imagem {
  height: 100%;
  width: 100%;
  object-fit: cover;
}
.paragrafo {
  max-width: 536px;
  line-height: 30px;
}
@media (max-width: 1024px) {
  .bg-inicial {
    box-shadow: none;
  }
}
@media (max-width: 640px) {
  .titulo {
    font-size: 2.3rem;
  }
  .titulo span {
    font-size: 3rem;
  }
}
</style>
