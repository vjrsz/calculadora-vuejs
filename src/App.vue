<template>
    <div class="container d-flex flex-column w-100 h-100 align-items-center justify-content-center">
        <h1 class="mb-3">Calculadora</h1>
        <Calculator />
    </div>
</template>
<script>

import {defineComponent} from "vue";
import Calculator from "@/components/Calculator.vue";

export default defineComponent({
    components: {Calculator}
})
</script>
<style>
html,body,#app{
    margin: 0px;
    width: 100%;
    height: 100%;
}
</style>