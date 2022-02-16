<template>
  <section class="trabalhos">
      <div class="container py-4">
        <div class="row py-3">
          <div class="col-12 col-md-6">
            <div id="carouselExampleControls" class="carousel slide mb-4" data-bs-ride="carousel">
              <div class="carousel-inner">
                <div class="carousel-item img-1 active">
                </div>
                <div class="carousel-item img-2">
                </div>
                <div class="carousel-item img-3">
                </div>
              </div>
              <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
              </button>
            </div>
          </div>
          <div class="col-12 col-md-6">
            <div class="row row-cols-1 row-cols-md-2 g-4">
              <div class="col">
                <div class="card">
                  <video autoplay muted loop>
                    <source src="@/assets/cozinha_video.mp4" type="video/mp4">
                    <p> Seu browser não suporta este conteúdo.</p> <!--fallback-->
                  </video>
                  <div class="card-body">
                    <h5 class="card-title">Cozinha em Nova Iguaçu</h5>
                    <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                  </div>
                </div>
              </div>
              <div class="col">
                <div class="card">
                  <img src="@/assets/deck.jpeg" class="card-img-top" alt="...">
                  <div class="card-body">
                    <h5 class="card-title">Deck de piscina em Niterói</h5>
                    <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                  </div>
                </div>
              </div>
              
              
            </div>
          </div>
          
        </div>
        
      </div>
    </section>
</template>

<script>
export default {

}
</script>

<style scoped>
.carousel-item {
  height: 550px;
  background-size: cover;
  background-position: center;
}

.img-1 {
  background-image: url("../assets/cozinha.jpeg");
}
.img-2 {
  background-image: url("../assets/balcao.jpeg");
}
.img-3 {
  background-image: url("../assets/cozinha-3.jpeg");
}
.trabalhos .card {
  background: sienna;
}

.trabalhos .card-body h5,
.trabalhos .card-body p {
  color: #eee;
}
</style>