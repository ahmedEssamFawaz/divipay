<template>
  <div class="home">
    <Navbar />
    <Carsoul />
    <Grid />
    <Clients />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'
import Carsoul from '@/components/Carsoul.vue'
import Grid from '@/components/Grid.vue'
import Clients from '@/components/Clients.vue'

export default {
  name: 'Home',
  components: {
    Navbar,
    Carsoul,
    Grid,
    Clients
  }
}
</script>
