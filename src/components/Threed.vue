
<script setup>
import { TresCanvas } from '@tresjs/core';
</script>

<template>
  <div id="canvas">
    <TresCanvas
      clear-color="#82DBC5"

    >
      <TresPerspectiveCamera
        :position="[3, 3, 3]"
        :look-at="[0, 0, 0]"
      />
      <TresMesh>
        <TresTorusGeometry :args="[1, 0.5, 16, 32]" />
        <TresMeshBasicMaterial color="orange" />
      </TresMesh>
      <TresAmbientLight :intensity="1" />
    </TresCanvas>
  </div>
</template>

<style>
#canvas {
  width: 500px; /* Set width */
  height: 500px; /* Set height */
  margin: auto;
  border: 1px solid #ccc; /* Optional for debugging */
}

TresCanvas {
  width: 100%; /* Make it fit the container */
  height: 100%;
}
</style>
