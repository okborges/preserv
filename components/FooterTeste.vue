<template>
  <footer class="footer-bg">
    <div class="footer container">
      <img src="../static/logo_claro.svg" alt="Bikcraft" />
      <div class="footer-contato">
        <h3 class="font-2-l-b cor-0">Contato</h3>
        <ul class="font-2-m cor-5">
          <li><a href="tel:+552199999999">+55 21 9999-9999</a></li>
          <li>
            <a href="mailto:contato@bikcraft.com">contato@bikcraft.com</a>
          </li>
          <li>Rua Ali Perto, 42 - Botafogo</li>
          <li>Rio de Janeiro - RJ</li>
        </ul>
        <div class="footer-redes">
          <a href="">
            <img src="" alt="" />
          </a>
          <a href="">
            <img src="" alt="" />
          </a>
          <a href="./">
            <img src="../static/WhatsApp.svg" alt="" />
          </a>
        </div>
      </div>
      <div class="footer-informacoes">
        <h3 class="font-2-l-b cor-0">Informações</h3>
        <nav>
          <ul class="font-1-m cor-5">
            <li><a href="./bicicletas.html">Bicicletas</a></li>
            <li><a href="./seguros.html">Seguros</a></li>
            <li><a href="./contato.html">Contato</a></li>
            <li><a href="./termos.html">Termos e Condições</a></li>
          </ul>
        </nav>
      </div>
      <p class="footer-copy font-2-m cor-6">
        Bikcraft © Alguns direitos reservados.
      </p>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.footer-bg {
  background-color: var(--cor-12);
}

.footer {
  display: grid;
  grid-template-columns: 3fr 5fr 4fr;
  gap: 40px;
  padding-top: 60px;
  padding-bottom: 60px;
}

.footer h3 {
  margin-bottom: 32px;
}

.footer-contato ul {
  margin-bottom: 32px;
}

.footer-contato li:nth-child(even):after {
  content: "";
  display: block;
  max-width: 360px;
  height: 2px;
  background: var(--cor-11);
  margin-top: 16px;
}

.footer li {
  margin-bottom: 16px;
}

.footer-redes {
  display: flex;
  gap: 32px;
}

.footer a:hover {
  color: var(--cor-0);
}

.footer-copy {
  grid-column: 1/-1;
  margin-top: 40px;
}

@media (max-width: 800px) {
  .footer > img {
    display: none;
  }
  .footer {
    grid-template-columns: 1fr 1fr;
  }
}

@media (max-width: 600px) {
  .footer {
    grid-template-columns: 1fr;
    gap: 60px;
  }
  .footer-copy {
    margin-top: 0px;
  }
}
</style>
