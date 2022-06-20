<template>
<div class="transition">
    
</div>
</template>

<script setup>

</script>

<style scoped>

@keyframes abc {
    0% {
        
    }
    to {
        background-color: aqua;
        width: 200px;
    }
}
.transition{
    height: 100px;
    width: 100px;
    background-color: blueviolet;
    animation-duration: 2s;
    

}
.transition:hover{
    animation-name: abc;
}

</style>z