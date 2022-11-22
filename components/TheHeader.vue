<template>
  <header class="block max-w-6xl p-5 mx-auto justify-between lg:flex">
    <a href="/" class="flex justify-center mb-3 lg:justify-start lg:mb-0">
      <img src="~/assets/icon/logo_V3.svg" alt="" width="214" />
    </a>
    <nav>
      <ul class="header-menu flex flex-wrap gap-6 justify-center sm:gap-10">
        <li><a href="/">Home</a></li>
        <li><a href="/#servicos">Serviços</a></li>
        <li><a href="/#clientes">Clientes</a></li>
        <li><a href="/#contato">Contato</a></li>
        <li><a href="/#produtos">Sobre nós</a></li>
      </ul>
    </nav>
  </header>
</template>

<style lang="scss" scoped>
header {
  nav {
    ul {
      li {
        a {
          display: inline-block;
          font-size: 20px;
          font-weight: 400;
          color: #0ea5e9;
          padding: 1rem 0rem;
          position: relative;
        }
        a:after {
          content: '';
          display: block;
          height: 0.125rem;
          width: 0%;
          background-color: #006490;
          margin-top: 0.25rem;
          position: absolute;
        }
        a:hover:after {
          transition: 0.3s;
          width: 100%;
        }

        a:hover {
          color: #006490;
        }
      }
    }
  }
}

@media (max-width: 991px) {
  header {
    nav {
      ul {
        li {
          a {
            font-size: 0.875rem;
            padding: 0.625rem 0.875rem;
            border-radius: 0.25rem;
            color: #d1f4ff;
            background-color: #14668e;
          }
          a:hover {
            color: #d1f4ff;
            background-color: #0a4c73;
          }
          a:after {
            display: none;
          }
        }
      }
    }
  }
}
</style>
