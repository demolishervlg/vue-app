<template>
    {{ date }}
</template>

<script setup>
    let date = new Date().toLocaleDateString('ru-RU');
</script>