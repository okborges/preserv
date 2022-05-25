<template>
  <div class="conteudo"></div>
</template>

<script>
export default {};
</script>

<style>
.conteudo {
  height: 100vh;
  width: 100%;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  background-image: url(https://images.unsplash.com/photo-1652535874141-03505f512722?crop=entropy&cs=tinysrgb&fm=jpg&ixlib=rb-1.2.1&q=80&raw_url=true&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1026);
  transition: 5s;

  animation-name: animate;
  animation-direction: alternate-reverse;
  animation-play-state: running;
  animation-duration: 10s;
  animation-fill-mode: forwards;
  animation-iteration-count: infinite;
}
@keyframes animate {
  0% {
    background-image: url(https://images.unsplash.com/photo-1652538893053-fe348c9a9440?crop=entropy&cs=tinysrgb&fm=jpg&ixlib=rb-1.2.1&q=80&raw_url=true&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170);
  }
  20% {
    background-image: url(https://images.unsplash.com/photo-1590943873908-03d0dbd6c04e?ixlib=rb-1.2.1&raw_url=true&q=80&fm=jpg&crop=entropy&cs=tinysrgb&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170);
  }
}
</style>
