<template>
  <div class="renovacao">
    <img class="hidden lg:block" src="../static/img/instalacao.webp" />
    <div class="pl-0 sm:pl-16">
      <h2 class="pb-10">Condicionamento e renovação de ar</h2>
      <div class="pontos">
        <div class="conteiner-texto">
          <p>Consultoria e Assessoria Técnica.</p>
          <p>Projetos e As Built.</p>
          <p>Manutenção preventiva, preditiva e corretiva.</p>
          <p>
            Implantação de sistemas de condicionamento de ar, ventilação e
            exaustão.
          </p>
        </div>
        <div class="conteiner-texto">
          <p>Retrofit</p>
          <p>Adequação de sistemas à conformidade de normas técnicas.</p>
          <p>
            PMOC - Plano de manutenção, operação e controle. Monitoramento,
            gestão de eficiência energética em sistemas de condicionamento de
            ar.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.renovacao {
  display: grid;
  grid-template-columns: 1fr 2fr;
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
  width: 520px;
  height: 500px;
  object-fit: cover;
}
.pontos {
  display: grid;
  grid-template-columns: 1fr 1fr;
  max-width: 900px;
  gap: 15px;
}
.pontos p {
  font-family: "Roboto";
  font-weight: 500;
  font-size: 16px;
  line-height: 36px;
  color: #c4c4c4;
  padding-bottom: 20px;
}
.conteiner-texto {
  max-width: 380px;
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
