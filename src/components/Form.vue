<template>
  <section class="formulario" id="formulario">
      <div class="container py-4">
        
        <div class="row py-3 justify-content-between">
          <div class="col-12 col-md-6">
            <h2 class="mb-4">Preencha e entraremos em contato com você</h2>
            <form method="post" action="http://localhost:8081/form/save">
              <label for="name" class="form-label mb-1">Como deseja ser chamado? </label>
              <input type="text" id="name" name="name" class="form-control mb-3" v-model="name" placeholder="Digite seu nome" required>
              <label for="email" class="form-label mb-1">Para qual e-mail posso responder? </label>
              <input type="email" id="email" name="email" class="form-control mb-3" v-model="email" placeholder="Digite seu e-mail" required>
              <label for="tel" class="form-label mb-1">Deseja um atendimento por Whatsapp? </label>
              <input type="tel" id="tel" name="tel" class="form-control mb-3" v-model="tel" placeholder="Digite seu número" required>
              <label for="project" class="form-label mb-1">Conte-nos sobre seu projeto</label>
              <textarea class="form-control" name="project" id="project" v-model="project" cols="30" rows="5" placeholder="Digite sua mensagem" required></textarea>
              <small class="d-block mb-4">* Atendemos somente no estado do Rio de Janeiro</small>
              <button type="submit" class="btn btn-dark mb-5 mb-md-0">Solicitar orçamento</button>
            </form>
          </div>
          <div class="col-12 col-md-5">
            <h2 class="mb-4">Nossa loja se encontra aqui</h2>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d920.5528120012832!2d-43.65710986070922!3d-22.645911081741772!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x994fde26adb2cf%3A0xf0919610de13ed99!2sR.%20Cel.%20Em%C3%ADdio%20Lemos%2C%20216%20-%20S%C3%A3o%20Jorge%2C%20Japeri%20-%20RJ%2C%2026435-250!5e0!3m2!1spt-BR!2sbr!4v1626279764209!5m2!1spt-BR!2sbr" width="600" height="450" style="border:0; max-width: 100%;" allowfullscreen="" loading="lazy"></iframe>
          </div>
        </div>
      </div>
    
    </section>
</template>

<script>
export default {
  name: "Form",
}
</script>

<style scoped>

form label {
  font-weight: bold;
}

form textarea {
  resize: none;
}
</style>