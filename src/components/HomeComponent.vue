<template>
    <h1>Home Component</h1>
    <FirstPage @fromChild="childFunctionExicuted"></FirstPage>
</template>

<script setup lang="ts">
    import FirstPage from "./FirstPageComponent.vue"

    function childFunctionExicuted(value: number){
        alert(value)
    }
</script>