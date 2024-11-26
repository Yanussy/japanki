
<template>
  <MDBNavbar id = "navbar" expand="lg" light bgColor="light">
    <MDBContainer>
      <MDBNavbarBrand href="#">japanki</MDBNavbarBrand>
    </MDBContainer>
  </MDBNavbar>
</template>

<script>
import { MDBContainer, MDBNavbar, MDBNavbarBrand } from 'mdb-vue-ui-kit';

export default {
  components: {
    MDBContainer,
    MDBNavbar,
    MDBNavbarBrand,
  },
};
</script>

<style>
#navbar{
  position: absolute;
  top:0;
  width:100%;
}

/* Add any custom styles for the navbar here */
</style>
