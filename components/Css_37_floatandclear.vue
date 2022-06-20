<template>
<div class="floatandclear">
    <div class="content"> content</div>
    <div class="sidebar">sidebar</div>
    <div class="futter"><p>footer</p></div>
</div>
</template>

<script setup>

</script>

<style scoped>
.content{
    background-color: aqua;
    width: 70%;
    height: 200px;
    float: left;
}

.sidebar{
    background-color: blueviolet;
    width: 30%;
    height: 150px;
    float: left;
}
.futter{
    background-color: yellowgreen;
    clear: left;
}
.floatandclear{
    border: 2px solid red;
    overflow: auto;
    
}

</style>z