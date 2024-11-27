<template>
  <MDBCard text="center">
    <MDBCardHeader>Featured</MDBCardHeader>
    <MDBCardBody>
      <MDBCardTitle>Special title treatment</MDBCardTitle>
      <MDBCardText>
        With supporting text below as a natural lead-in to additional content.
      </MDBCardText>
      <MDBBtn tag="a" href="#!" color="primary">Go somewhere</MDBBtn>
    </MDBCardBody>
    <MDBCardFooter class="text-muted">2 days ago</MDBCardFooter>
  </MDBCard>
</template>
<script setup lang="ts">
  import { MDBCard, MDBCardBody, MDBCardHeader, MDBCardTitle, MDBCardText, MDBCardFooter, MDBBtn } from "mdb-vue-ui-kit";
</script>
