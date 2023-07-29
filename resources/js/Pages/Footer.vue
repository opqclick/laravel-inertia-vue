<script setup>
import Link from './Link.vue'
</script>

<template>
  <div style="margin-top: 400px">
    <Link
        href="/test"
        name="Test"
        component="Test"
    ></Link>

    <Link
        href="/about"
        name="About"
        component="About"
    ></Link>
  </div>

</template>

<style>
.active{
  text-decoration: underline;
  color: yellow;
}
</style>