<template>
  <header class="bg-clarinho px-5">
    <div class="max-w-6xl mx-auto py-6">
      <div class="centralizar">
        <a href="/">
          <img src="../static/logo_V3.svg" alt="" width="214" />
        </a>
        <nav>
          <ul class="header-menu flex flex-wrap gap-5 justify-center sm:gap-10">
            <li><a href="./">Home</a></li>
            <li><a href="#servicos">Serviços</a></li>
            <li><a href="#produtos">Produtos</a></li>
            <li><a href="#clientes">Clientes</a></li>
            <li><a href="#contato">Contato</a></li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
.bg-clarinho {
  background-color: #fafafa;
}
.centralizar {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  align-items: center;
  justify-content: space-between;
}
.header-menu a {
  display: inline-block;
  font-family: "Poppins", sans-serif;
  font-size: 1.125rem;
  font-weight: 400;
  color: #0ea5e9;
  padding: 16px 0px;
  position: relative;
}
.header-menu a:after {
  content: "";
  display: block;
  height: 2px;
  width: 0%;
  background-color: #0ea5e9;
  margin-top: 4px;
  position: absolute;
}
.header-menu a:hover:after {
  transition: 0.3s;
  width: 100%;
}

.header-menu a:hover {
  color: #006490;
}

@media (max-width: 800px) {
  .centralizar {
    justify-content: center;
  }
  .header-menu a {
    background-color: #e0f2fe;
    padding: 12px 16px;
    border-radius: 4px;
  }
  .header-menu a:hover {
    background-color: #7dd3fc;
  }
  .header-menu a:after {
    display: none;
  }

  @media (max-width: 640px) {
    .header-menu {
      gap: 12px;
    }
    .header-menu a {
      padding: 8px 12px;
      font-size: 14px;
    }
  }
}
</style>
