<script setup lang="ts">
import VueFitText from './components/VueFitText.vue'
const lines = [
  "dehino ’smin yathā dehe",
  "kaumāraṁ yauvanaṁ jarā",
  "tathā dehāntara-prāptir",
  "dhīras tatra na muhyati"
]
</script>

<template>
  <VueFitText
    :lines="lines"
  />
</template>
