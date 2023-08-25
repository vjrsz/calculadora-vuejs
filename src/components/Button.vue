<template>
    <div class="col-3 m-0 p-0" :class="{ 'col-6':double, 'col-9':triple }">
        <button
            class="btn btn-outline-primary w-100 fs-5 fw-bold py-3 rounded-0"
            @click="$emit('onCalcButtonClick', label)"
            :class="{  'text-danger': operation }">
            {{ label }}
        </button>
    </div>
</template>
<script>
    export default{
        props : {
            label: {},
            operation: {type: Boolean},
            double: {type: Boolean},
            triple: {type: Boolean},
        }
    }
</script>
<style scoped>
</style>