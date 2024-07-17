<template>
    <h1>
        First Page Component is About Event Arguments
    </h1>
    <button @click="$emit('fromChild', 20)">Emit</button>
</template>