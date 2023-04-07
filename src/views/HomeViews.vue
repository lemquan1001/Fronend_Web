<template>
  <v-app>
    <Navbar class="index" />
    <Dashboard />
    <Footer />
  </v-app>
</template>

<script>
  import Navbar from '../components/NavBar.vue'
  import Dashboard from '../components/DashBoard.vue'
  import Footer from '../components/FooTer.vue'

  export default {
    name: 'HomeViews',

    components: {
      Navbar,
      Dashboard,
      Footer

    },
  }
</script>
<style scoped>
.index{
  z-index: 9999;
}
</style>