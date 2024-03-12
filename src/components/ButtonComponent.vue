<template>
 <button class="btn" :class="`${color}`">{{ label }}</button>
</template>

<script lang="ts" setup>
defineProps<{
    label: string;
    color: string;
}>();
</script>

<style lang="scss" scoped>
.btn{
    border: none;
    background-color: blue;
    color: white;
    box-shadow: none;
    padding: 15px 30px;
    &.red {
        background-color: red;
    }
    &.blue {
        background-color: blue;
    }
}
</style>