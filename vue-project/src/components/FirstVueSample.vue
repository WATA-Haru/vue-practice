<script setup>
import { ref } from 'vue'

const sample = ref('hello!!! first vue')
</script>

<template>
<h1>{{ sample }}</h1>
</template>