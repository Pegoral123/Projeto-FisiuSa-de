<template>
  <section id="atendimento" class="container">
    <div class="row">
      <div class="col-8">
        <div class="amarelo border border-dark">
          <div class="text-center py-4">
            <h2>Explique o que você precisa</h2>
            <h4>Receba até 2 orçamentos grátis, online!</h4>
          </div>
          <div class="py-4 px-4">
            <h4>Qual serviço de fisioterapia você procura?</h4>
            <div class="p-2">
              <select class="form-select" aria-label="Default select example">
                <option selected>Selecione uma opção</option>
                <option value="1">Pilates</option>
                <option value="2">Fisioterapia esportiva</option>
                <option value="3">outros</option>
              </select>
            </div>
            <div class="text-center pt-3">
              <button type="button" class="btn btn-primary col-8">
                Proximo
              </button>
            </div>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div>
          <h4>Avaliações de quem contratou os serviço FisiuSaude</h4>
      </div>
         <div class="col-12 py-4">
           <div class="border border-dark p-3">
         <div > 
              <h5>João Motta avaliou:</h5>
          </div>
         <div>
            <a>A melhore profissionai da área que tem na minha região. Super recomendo.</a>
           </div>
           <div>
             <i class="bi bi-star-fill font"></i>
             <i class="bi bi-star-fill font"></i>
             <i class="bi bi-star-fill font"></i>
             <i class="bi bi-star-fill font"></i>
             </div>
           </div> 
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "atendimentoUsuario",
};
</script>

<style>
.branco {
    background-color: #fefefe
}

.cinza {
    background-color: #b1ada1
}

.amarelo {
    background-color: #f8866b
}
.font{
  font-size: 20px;
  color: #ecc661
}

</style>