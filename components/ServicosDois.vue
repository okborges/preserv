<template>
  <div class="renovacao pb-8 sm:pb-16">
    <div class="pl-0 sm:pl-16">
      <h2 class="pb-5 sm:pb-10">Engenharia</h2>
      <div class="pontos">
        <div class="conteiner-texto">
          <p>
            Diagnóstico e análise de consumo e demanda de recursos (água,
            energia elétrica, gás, temperatura e emissão de CO2).
          </p>
          <p>Rastreabilidade e gestão do ciclo de vida útil dos ativos.</p>
          <p>QSMS - Qualidade, Segurança, Meio Ambiente e Saúde.</p>
        </div>
      </div>
    </div>
    <img class="hidden lg:block" src="../static/img/22.jpg" />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.renovacao {
  display: grid;
  grid-template-columns: 2fr 1fr;
  margin-left: auto;
  margin-right: auto;
  max-width: 1700px;
  align-items: center;
}
.renovacao h2 {
  font-weight: 500;
  font-size: 40px;
  line-height: 60px;
  color: #0ea5e9;
}
.renovacao img {
  width: 720px;
  height: 700px;
  object-fit: cover;
}
.pontos {
  max-width: 900px;
}
.pontos p {
  font-family: "Roboto";
  font-weight: 500;
  font-size: 16px;
  line-height: 36px;
  color: #c4c4c4;
  padding-bottom: 20px;
}

.conteiner-texto p {
  position: relative;
}
.conteiner-texto p::before {
  content: "";
  display: block;
  height: 4px;
  width: 4px;
  background-color: #0ea5e9;
  border-radius: 50%;
  left: -10px;
  top: 17px;
  position: absolute;
}

@media (max-width: 1024px) {
  .renovacao {
    grid-template-columns: 1fr;
  }
}
@media (max-width: 640px) {
  .pontos {
    grid-template-columns: 1fr;
    gap: 0px;
  }
  .renovacao h2 {
    font-size: 32px;
  }
}
</style>
