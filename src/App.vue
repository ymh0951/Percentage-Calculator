<template>
<main class="main">
  <PercentageCalculatorCard />
</main>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import PercentageCalculatorCard from '@/components/PercentageCalculatorCard.vue'

export default defineComponent({
  components: {
    PercentageCalculatorCard,
  },
})
</script>

<style lang="scss">
body {
  margin: 0;
}

.main {
  width: 100vw;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #f5f5f5;
}
</style>