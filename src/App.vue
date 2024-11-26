
<template>
  <header>
    <Navbar />
  </header>
  <div>
    <footer>
  <Footer />
  </footer>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';


export default {
  components: {
    Navbar,
    Footer,
  },
};
</script>

<style>

#navbarContainer {

}

/* Ensure the body and app have no padding/margin that might center the navbar */




#app {
  min-height: 100%;
  display: flex;
  flex-direction: column;
}
</style>
