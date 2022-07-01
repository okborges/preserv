<template>
  <section class="bg-inicial px-5">
    <div class="max-w-6xl mx-auto">
      <div class="grid lg:grid-cols-2 gap-5">
        <div class="imagem">
          <img src="../static/img/img-2.webp" alt="" />
        </div>
        <div class="pt-28">
          <h2 class="titulo pb-9">
            Benefícios de um
            <span class="text-azul-3">Ambiente Climatizado</span>.
          </h2>
          <p class="text-cinza-claro text-2xl pb-7">
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
  box-shadow: inset 0 -40px #fafafa, inset 0 40px #fafafa;
}
.titulo {
  color: #ffffff;
  font-size: 4rem;
  font-weight: 700;
  line-height: 145%;
}
.titulo span {
  font-size: 4.5rem;
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
  position: absolute;
}
.imagem {
  height: 100%;
  width: 100%;
  object-fit: cover;
}
</style>
