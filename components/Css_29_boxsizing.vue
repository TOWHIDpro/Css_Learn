<template>
<div class="boxsizing">
    <div id="div1">div1</div>
    <hr>
    <div id="div2">div2</div>
</div>
</template>

<script setup>

</script>

<style scoped>
#div1{
    background-color: blueviolet;
    width: 600px;
    height: 150px;
}

#div2{
    background-color: chocolate;
    width: 600px;
    height: 150px;
    padding: 50px;
    border: 5px solid black;
    box-sizing: border-box;
}
</style>z