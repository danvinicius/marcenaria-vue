<template>
  <footer class="footer" id="footer">
        <div class="container">
          <div class="row py-5">
            <div class="col-12 col-md-4">
              <h3 class="mb-4">Entre em contato</h3>
              <address>
                <p class="mb-2">
                  <span>Endereço:</span>
                  R. Cel. Emídio Lemos, 216, Centro, Japeri-RJ
                </p>
                <p class="mb-2">
                  <span>Telefone:</span>
                  2198133-7681
                </p>
                <p class="mb-2">
                <span>Falar com:</span>
                Marcos Vinicius
              </p>
              </address>
            </div>
          </div>
        </div>
        <div class="copyright pb-5">
            <div class="col-12">
              <p class="text-center">Marcenaria & Decorações <span id="data"></span> - todos os direitos reservados</p>
          </div>
          
        </div>
    </footer>
</template>

<script>
export default {

}
</script>

<style scoped>
footer address {
  position: relative;
  padding-left: 20px;
}
footer address::before {
  content: "";
  position: absolute;
  left: 2px;
  height: 100%;
  width: 5px;
  background: #fff;
}

footer {
  background: sienna;
}

footer > span {
  display: block;
}

footer h3,
footer p {
  color: #eee;
  margin: 0;
}

.copyright {
  background: sienna;
  font-size: 20px;
}
</style>