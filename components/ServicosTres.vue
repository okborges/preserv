<template>
  <div class="renovacao pb-8 sm:pb-16">
    <img class="hidden lg:block" src="../static/img/23.jpeg" />
    <div class="pl-0 sm:pl-16">
      <h2 class="pb-5 sm:pb-10">Serviços de Infra-estrutura</h2>
      <div class="pontos">
        <div class="conteiner-texto">
          <p>Manutenção Industrial e Predial.</p>
          <p>Obras de Infraestrutura.</p>
          <p>Análise Técnica e Operacional de Sistemas de Infraestrutura.</p>
          <p>
            Planejamento, coordenação e programação de intervenções através de
            ferramentas de gestão de ativos.
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
