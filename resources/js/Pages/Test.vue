<script setup>
import {ref} from "vue";
import Footer from "./Footer.vue";
const count = ref(0);
</script>

<template>
  Hello!
  <button @click="$event => count++">+</button>
  {{ count }}
  <button @click="$event => count--">-</button>

  <Footer/>
</template>