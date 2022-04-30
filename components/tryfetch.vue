<template>
    <div>
        Page visits: {{ data[1].website }}
    </div>
</template>
<script setup lang="ts">
    const { data } = await useAsyncData('count', () => $fetch('http://127.0.0.1:8000/api/view/platform'))
</script>
<style lang="">
    
</style>