<template>
    <article class="percentage-calculator-card">
        <h1 class="title">퍼센트 계산기</h1>
    </article>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    setup () {
        

        return {}
    }
})
</script>

<style lang="scss" scoped>
.percentage-calculator-card {
    width: 95%;
    max-width: 500px;
    padding: 30px;
    margin: 15px;
    border-radius: 15px;
    background-color: #fff;

    .title {
        font-weight: 700;
        font-size: 24px;
    }
}
</style>