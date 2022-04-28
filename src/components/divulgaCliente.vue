<template>
  <section id="propaganda1" class="pt-3">
    <div class="p-0">
      <div class="container">
        <div
          id="carouselExampleControls"
          class="carousel slide"
          data-bs-ride="carousel"
        >
          <div class="carousel-inner">
            <div class="carousel-item active imgBG1">
              <!-- <img src="img/produtos/p1.jpg" class="d-block w-100" alt="..."> -->
            </div>
            <div class="carousel-item imgBG2">
              <!-- <img src="img/produtos/produto02.jpg" class="d-block w-100" alt="..."> -->
            </div>
            <div class="carousel-item imgBG3">
              <!-- <img src="img/produtos/p3.jpg" class="d-block w-100" alt="..."> -->
            </div>
          </div>
          <button
            class="carousel-control-prev"
            type="button"
            data-bs-target="#carouselExampleControls"
            data-bs-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next"
            type="button"
            data-bs-target="#carouselExampleControls"
            data-bs-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<script scoped>
export default {};
</script>

<style >
.cinza {
  background-color: #b1ada1;
}

.imgBG1,
.imgBG2,
.imgBG3 {
  background-size: cover;
  background-position: center;
  min-height: 500px;
}
.imgBG1 {
  background-image: url(../assets/fundoFisiuSaude.jpeg);
}
.imgBG2 {
  background-image: url(../assets/fotoCliente.jpeg);
}
.imgBG3 {
  background-image: url(../assets/logoCliente.jpeg);
}
</style>