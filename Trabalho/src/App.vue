<template>
  <div>
    <Navbar />
    <RouterView />
    <Footer />
  </div>
</template>
  


<script>

import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';

export default {
name:'App',
components:{
  Navbar,
  Footer
}

}
</script>

<style>

</style>
<script>

</script>


<style scoped>

</style>
