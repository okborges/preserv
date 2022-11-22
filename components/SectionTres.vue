<template>
  <section id="produtos" class="px-5 bg-cinza-900 mb-16">
    <div class="max-w-6xl mx-auto grid lg:grid-cols-2">
      <div class="px-3">
        <img src="~/assets/img/img-2.webp" alt="" />
      </div>
      <div class="text-white self-center">
        <h2>Benefícios de um Ambiente Climatizado</h2>
        <p class="text-xl pb-7 paragrafo">
          O ar-condicionado é considerado um item indispensável para todos os
          tipos de ambientes e já deixou de ser um item de luxo para se tornar
          um item necessário em diversos locais.
        </p>
        <a href="/beneficios" class="saiba">SAIBA MAIS</a>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
section {
  box-shadow: inset 0 -25px #eef0f5, inset 0 25px #eef0f5;
  h2 {
    font-size: clamp(1rem, 10vw, 3rem);
    margin-bottom: 20px;
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
    color: #0ea5e9;
    font-size: 1.5rem;
    font-weight: 700;
    letter-spacing: 0.05em;
    position: relative;
  }
  a::after {
    content: '';
    display: block;
    width: 100%;
    height: 3px;
    background-color: #0ea5e9;
    margin-top: 4px;
  }

  @media (max-width: 991px) {
    img {
      display: none;
    }
  }
}
</style>
