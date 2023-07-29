<script setup>
import {Link} from "@inertiajs/vue3";
import { defineProps } from 'vue';

defineProps(["name", "component", "href"]);
</script>

<template>
  <Link :class="$page.component == component && 'active'" preserve-scroll :href="href">
    {{ name }}
  </Link>
</template>
