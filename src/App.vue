<template>
  <NavBar/>
  <Portfolio/>
  <Rodape/>
</template>

<script>
import NavBar from './components/NavBar.vue';
import Portfolio from './components/Portfolio.vue';
import Rodape from './components/Rodape.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    Portfolio,
    Rodape
  }
}
</script>