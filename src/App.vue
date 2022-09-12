<template>

  <div >
    <table>
      <tr><td><Dente/></td><td><Dente/></td><td><Dente/></td></tr>
    </table>
      
   
  </div>
  
</template>

<script>
import PrimeiroComponente from './components/PrimeiroComponente.vue'
import Dente from './components/Dente.vue';
export default {
  name: 'App',
  components: {
    PrimeiroComponente,
    Dente,
  }
}
</script>