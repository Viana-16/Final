<template>
  <div>
    <Navbar />
    <RouterView />
    <Footer />
  </div>
</template>
  


<script>

import Footer from './components/Footer.vue';
import Navbar from './components/Navbar.vue';

export default {
name:'App',
components:{
  Navbar,
  Footer
}

}
</script>


<style scoped>

</style>
