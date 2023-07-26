<script setup lang="ts">
import SakanaWidget from 'sakana-widget'
import { onMounted } from 'vue'

const sakana = new SakanaWidget()
onMounted(() => {
  sakana.mount('#sakana-widget')
})
</script>

<template>
  <div id="sakana-widget" class="fixed right-12 bottom-8" />
</template>

<style lang="scss">
@import 'sakana-widget/lib/index.css';
</style>
