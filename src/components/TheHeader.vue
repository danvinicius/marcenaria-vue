<template>
  <header class="header">
        <nav class="navbar navbar-expand-lg navbar-light p-3">
            <div class="container">
              <div class="logo-elipse me-5">
              <a class="navbar-brand header__logo" href="/">
                <img src="@/assets/logo-texto.svg" alt="">
              </a>
              </div>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse justify-content-between" id="navbarNavAltMarkup">
                <div class="navbar-nav pt-4 pt-md-0">
                  <a class="nav-link h5 me-3" href="#sobre">Sobre</a>
                  <a class="nav-link h5 me-3" href="#footer">Contato</a>
                  <router-link to="/">Portfólio</router-link>
                  <a href="#formulario"><button class="btn btn-dark">Agende uma visita</button></a>
                </div>
                
              </div>
            </div>
        </nav>
    </header>
</template>

<script>
export default {

}
</script>

<style scoped>
header {
  box-shadow: 0 1px 20px black;
}
nav {
  background: sienna;
}
.navbar-nav {
  display: flex;
  align-items: center;
}
nav a, nav .router-link-active {
  font-weight: bold;
  color: #fff !important;
  text-decoration: none;
  margin: 0;
}

nav .router-link-active {
  margin-right: 1rem;
  font-size: 20px;
}
.logo-elipse {
  background-color: #fff;
  width: 155px;
  height: 70px;
  border-radius: 50%;
}
.header__logo img {
  width: 135px;
  position: relative;
  top: 10px;
  left: 7px;
}

</style>