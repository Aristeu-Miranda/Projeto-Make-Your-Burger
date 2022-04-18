<template>
<div>
  <Banner />
  <div class="main-container">
    <h1>Monte você mesmo:</h1>
    <BurgerForm />
  </div>
</div>

</template>

<script>
import Banner from '../components/Banner.vue'
import BurgerForm from '../components/BurgerForm.vue'

export default {
  name: 'Home',
  components: {
    Banner,
    BurgerForm
  }
}

</script>
