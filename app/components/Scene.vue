<script setup lang="ts">
import { OrbitControls } from "@tresjs/cientos";
</script>

<template>
  <TresPerspectiveCamera :position="[4, 4, 4]" :look-at="[0, 2, 0]" />

  <Donut />

  <TresAxesHelper />
  <TresGridHelper />

  <OrbitControls />
</template>
