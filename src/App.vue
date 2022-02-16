<template>
  <TheHeader/>
  <main>
  <router-view/>
  </main>
  <TheFooter/>
</template>

<script>
import TheHeader from '@/components/TheHeader';
import TheFooter from '@/components/TheFooter';
export default {
  components: {
    TheHeader,
    TheFooter
  }
}
</script>
<style>
/*css reset*/ 

* {
  box-sizing: border-box;
}

body, ul, li, h1, h2, p {
  padding: 0;
  margin: 0;
}
ul {
  list-style: none;
}
body{
  font-family: "Montserrat", sans-serif;
  background: peachpuff;
}
a {
  color: #fff;
  text-decoration: none;
}
img {
  max-width: 100%;
  display: block;
}

</style>
