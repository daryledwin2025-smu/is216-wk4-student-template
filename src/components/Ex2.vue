<script setup>
import { ref } from 'vue'
let data = {
  src:"/assets/me.png",
  height:"400px",
  width: "200px"
}

// Add code here
</script>

<template>
  <!-- // do this using dictionary. and also add the height and width -->
  <!-- Add code here -->
   <img v-bind="data" alt="">
</template>
