<template>
  <nav class="navbar navbar-light bg-light border border-dark">
    <div class="container">
      <h1 class="navbar-brand">FisioSaúde</h1>
      <form class="d-flex">
        <button class="btn btn-outline-primary" type="button">
          Cadastra-se no site
        </button>
      </form>
    </div>
  </nav>
  <div class="cinza">
    <div><a>FisioSaúde</a> > <a>Saúde</a> > <a>Fisioterapia</a></div>
  </div>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style>
.border {
  border-block-color: #f9876c;
}
</style>