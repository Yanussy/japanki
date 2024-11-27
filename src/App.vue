
<template>
  <header>
    <Navbar />
  </header>
  <main>
    <div class ="Tcontainer">

         <Threed/>
  <div></div>
    </div>
  </main>

    <footer>
  <Footer />
  </footer>

</template>

<script>
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';
import Threed from './components/Threed.vue';
import Card from './components/Card.vue';

export default {
  components: {
    Navbar,

    Threed,
    Footer,
  },
};
</script>

<style>

 .Tcontainer {
   display:flex;
   justify-content: center;
   padding-top: 100px;

}

/* Ensure the body and app have no padding/margin that might center the navbar */




</style>
