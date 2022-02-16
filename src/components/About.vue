<template>
  <section class="sobre" id="sobre">
      <div class="container py-4">
        <div class="row py-3">
          <h2 class="mb-4 text-center"><u> Quem sou eu</u></h2>
          <div class="col-md-3">
            <div class="img-container mb-4 mb-md-0">
              <img src="@/assets/me.jpeg" alt="">
            </div>
          </div>
          <div class="col-md-4">
            <p class="sobre__paragraph fs-5">
              <strong>Marcos Vinícius</strong>, pai do Filipe, do Daniel e da Ana Júlia. 
              Apaixonado por marcenaria desde os meus 13 anos de idade, 
              quando comecei a trabalhar. Sempre disposto a aprender e a dar o meu melhor. 
              Morador de Japeri-RJ, amo minha cidade, meus filhos e, acima de tudo, Deus.
          </p></div>
        </div>
      </div>
    </section>
</template>

<script>
export default {

}
</script>

<style scoped>
.sobre {
  background: sienna;
}

.sobre h2,
.sobre p {
  color: #eee;
}

.sobre__paragraph {
  line-height: 1.6;
}
</style>