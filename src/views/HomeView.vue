<template>
  <div class="home">
    <Navbar />
    <H1 class="text-center">Ini Landing Pagenya</H1>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'HomeView',
  components: {
    Navbar
  }
}
</script>
