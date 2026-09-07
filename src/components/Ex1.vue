<script setup>
import { ref } from 'vue'
const message = ref("Choose fav");
const fruits = ref(["apple","orange"])
// Add code here
// challenge: use array
</script>

<template>
  {{ message }}

  <!-- <label for=""> <input type="radio" name="fruit" /> {{ fruit1 }} </label>
  <label for=""> <input type="radio" name="fruit" /> {{ fruit2 }} </label>
  <label for=""><input type="radio" name="fruit" /> {{ fruit3 }} </label> -->
  <label v-for="fruit in fruits" :key="fruit">
    <input type="radio" name="fruit">{{ fruit }}
  </label>
</template>

<style scoped></style>
