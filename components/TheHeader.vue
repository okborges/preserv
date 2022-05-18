<template>
  <header class="mx-8">
    <div class="max-w-6xl mx-auto sm:pt-7">
      <div
        class="flex justify-center items-center mt-4 sm:justify-between sm:mt-12"
      >
        <a href="/" class="logo"><LogoPreserv /></a>

        <div class="flex space-x-7">
          <nav class="hidden sm:flex">
            <ul class="nav space-x-4 flex font-bold">
              <li><a href="#sobreMim" class="p-2">Sobre</a></li>
              <li><a href="#projetos" class="p-2">Projetos</a></li>
              <li><a href="#" class="p-2">Contato</a></li>
            </ul>
          </nav>
        </div>
      </div>
      <nav class="flex justify-center mt-7 sm:hidden">
        <ul class="nav space-x-6 flex bloquinho font-bold">
          <li><a href="#">Sobre</a></li>
          <li><a href="#">Projetos</a></li>
          <li><a href="#">Contato</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
import TopHeader from "./TopHeader.vue";
import LogoPreserv from "./LogoPreserv.vue";
export default { components: { TopHeader, LogoPreserv } };
</script>

<style scoped>
.bg-header {
  background-color: #fafafa;
}

.fonte-azul {
  color: #0ea5e9;
}

.fonte-azul a:hover {
  color: #0c4a6e;
  transition: 0.3s;
}

.bloquinho li {
  background-color: #e0f2fe;
  padding: 8px;
  border-radius: 3px;
}
</style>
