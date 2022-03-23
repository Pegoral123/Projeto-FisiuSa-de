<template>
  <NavBar />
  <divulgaProduto />
  <atendimentoUsuario />
  <divulgaCliente />
  <rodapePage />
</template>

<script>
import NavBar from "./components/NavBar.vue";
import divulgaProduto from "./components/divulgaProduto.vue";
import atendimentoUsuario from "./components/atendimentoUsuario.vue";
import divulgaCliente from "./components/divulgaCliente.vue";
import rodapePage from "./components/rodapePage.vue";

export default {
  name: "App",
  components: {
    NavBar,
    divulgaProduto,
    atendimentoUsuario,
    divulgaCliente,
    rodapePage,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
