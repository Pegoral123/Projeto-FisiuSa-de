<template>
  <NavBar />
  <divulgaProduto />
  <atendimentoUsuario />
</template>

<script>
import NavBar from "./components/NavBar.vue";
import divulgaProduto from "./components/divulgaProduto.vue";
import atendimentoUsuario from "./components/atendimentoUsuario.vue";

export default {
  name: "App",
  components: {
    NavBar,
    divulgaProduto,
    atendimentoUsuario,
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
