<template>
    <div class="display d-flex justify-content-end border border-primary col-12 rounded-top-5">
        <p class="text-white fs-1 fw-bold my-auto">
            {{ value }}
        </p>
    </div>
</template>
<script>
    export default {
        props: ['value']
    }
</script>
<style scoped>
    .display{
        height: 100px;
    }
</style>