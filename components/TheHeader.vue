<template>
  <header>
    <div class="mx-8">
      <div class="max-w-6xl mx-auto sm:mt-9">
        <div
          class="flex justify-center items-center mt-4 sm:mt-0 lg:justify-between"
        >
          <NuxtLink to="/" class="logo"><LogoPreserv /></NuxtLink>

          <div class="flex space-x-7">
            <nav class="hidden lg:flex">
              <ul class="fonte-azul space-x-4 flex font-bold">
                <li><NuxtLink to="/" class="p-2">Home</NuxtLink></li>
                <li><a href="#servicos" class="p-2">Serviços</a></li>
                <li><a href="#produtos" class="p-2">Produtos</a></li>
                <li><a href="#clientes" class="p-2">Clientes</a></li>
                <li><a href="#contato" class="p-2">Contato</a></li>
              </ul>
            </nav>
          </div>
        </div>
        <nav class="flex justify-center mt-7 lg:hidden">
          <ul
            class="fonte-azul gap-6 flex flex-wrap bloquinho font-bold justify-center"
          >
            <li><a href="/">Home</a></li>
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
import LogoPreserv from "./LogoPreserv.vue";
export default { components: { LogoPreserv } };
</script>

<style scoped>
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
