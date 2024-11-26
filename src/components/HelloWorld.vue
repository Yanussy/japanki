<!-- <script setup> -->
<!-- defineProps({ -->
<!--   msg: { -->
<!--     type: String, -->
<!--     required: true, -->
<!--   }, -->
<!-- }) -->
<!-- </script> -->
<!---->
<!-- <template> -->
<!--   <div class="greetings"> -->
<!--     <h1 class="green">{{ msg }}</h1> -->
<!--     <h3> -->
<!--       успешно имаме джапанки -->
<!--          </h3> -->
<!--   </div> -->
<!-- </template> -->
<!---->
<!-- <style scoped> -->
<!-- h1 { -->
<!--   font-weight: 500; -->
<!--   font-size: 2.6rem; -->
<!--   position: relative; -->
<!--   top: -10px; -->
<!-- } -->
<!---->
<!-- h3 { -->
<!--   font-size: 1.2rem; -->
<!-- } -->
<!---->
<!-- .greetings h1, -->
<!-- .greetings h3 { -->
<!--   text-align: center; -->
<!-- } -->
<!---->
<!-- @media (min-width: 1024px) { -->
<!--   .greetings h1, -->
<!--   .greetings h3 { -->
<!--     text-align: left; -->
<!--   } -->
<!-- } -->
<!-- </style> -->

<template>
  <h1>{{ msg }}</h1>

  <p>
    <a href="https://vitejs.dev/guide/features.html" target="_blank">
      Vite Documentation
    </a>
    |
    <a href="https://v3.vuejs.org/" target="_blank">Vue 3 Documentation</a>
  </p>

  <MDBBtn color="primary" class="mb-3" @click="state.count++">
    count is: {{ state.count }}
  </MDBBtn>

  <p>
    Edit components/HelloWorld.vue to test hot module replacement.
  </p>

</template>

<script setup lang="ts">
  import { defineProps, reactive } from "vue";
  import { MDBBtn } from "mdb-vue-ui-kit";

  defineProps({
    msg: String,
  });

  const state = reactive({ count: 0 });
</script>

<style scoped>
  a {
    color: #42b983;
  }
</style>
