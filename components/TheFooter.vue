<template>
  <footer class="bg-black px-5">
    <div class="footer max-w-6xl mx-auto">
      <img src="../static/logo_claro.svg" alt="" />
      <div>
        <h3 class="text-white pt-2 pb-8 text-lg">CONTATO</h3>
        <ul class="itens-lista">
          <li><a href="tel:+551133843313">(11) 3384-3313</a></li>
          <li><a href="tel:+5511991662288">(11) 9 9166-2288</a></li>
          <li><a href="mailto:dir@preserv.eng.br">dir@preserv.eng.br</a></li>
          <li class="risco my-9"></li>
        </ul>
        <div class="flex gap-10">
          <a
            href="https://www.facebook.com/Preserv-Engenharia-1307261656113671/"
            ><img src="../static/Facebook.svg" alt=""
          /></a>
          <a href="https://www.instagram.com/preserv.engenharia/"
            ><img src="../static/Instagram.svg" alt=""
          /></a>
          <a href=""><img src="../static/WhatsApp.svg" alt="" /></a>
        </div>
      </div>
      <div>
        <h3 class="text-white pt-2 pb-8 font-medium text-lg">INFORMAÇÕES</h3>
        <nav>
          <ul class="itens-lista">
            <li><a href="#" class="font-medium">Serviços</a></li>
            <li><a href="#" class="font-medium">Contato</a></li>
            <li><a href="#" class="font-medium">Produtos</a></li>
            <li><a href="#" class="font-medium">Clientes</a></li>
          </ul>
        </nav>
      </div>
      <p class="footer-copy">Preserv © Todos os direitos reservados.</p>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  display: grid;
  grid-template-columns: 3fr 5fr 4fr;
  gap: 40px;
  padding-top: 60px;
  padding-bottom: 60px;
}

.itens-lista li {
  margin-bottom: 1rem;
}
.itens-lista a {
  color: #b2b2b2;
  font-size: 1.125rem;
}
.itens-lista a:hover {
  color: #ffffff;
}
.risco {
  content: "";
  display: block;
  max-width: 360px;
  height: 2px;
  background: #222222;
}
.footer-copy {
  color: #ffffff;
  font-size: 1.125rem;
  font-weight: 500;
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
