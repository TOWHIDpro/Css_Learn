<template>
<div class="viewport">
    <div class="div1"></div>
    <div class="div2"></div>
</div>
</template>

<script setup>

</script>

<style scoped>
.div1{
    background-color: blueviolet;
    width: 70%;
    height: 200px;
    float: left;
}
.div2{
    background-color: brown;
    width: 30%;
    height: 200px;
    float: left;
}

@media screen and (max-width: 1000px) {
    .div1{
        width: 50%;
    }
    .div2{
        width: 50%;
    }
}

@media screen and (max-width: 700px) {
    .div1{
        width: 100%;
    }
    .div2{
        width: 100%;
    }
}


</style>z