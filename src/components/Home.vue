
<template>
  <div class="home">
    <Navbar/>
  </div>
</template>

<script>
/* eslint-disable */
import Navbar from './Navbar.vue'
export default {
  name: 'HomePage',
  props: {
    welcomeMsg: String
  },
  components: {
    Navbar,
    Navbar
}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
