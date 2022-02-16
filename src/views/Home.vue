<template>
<section>
  <Carousel/>
  <About/>
  <Form/>
</section>
</template>

<script>
// @ is an alias to /src
import Carousel from '@/components/Carousel.vue'
import About from '@/components/About.vue'
import Form from '@/components/Form.vue'

export default {
  name: 'Home',
  components: {
    Carousel,
    About,
    Form
  }
}
</script>
