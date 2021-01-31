<template>
  <v-container>
    <Tarjeta></Tarjeta>
  </v-container>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Tarjeta from '@/views/Tarjetas.vue'
export default {
  name: 'Home',
  components: {
    Tarjeta
  }
}
</script>
