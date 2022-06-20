<template>
<div class="position">
    <div id="one"></div>
    <div id="two"></div>
    <div id="three"></div>
</div>
</template>

<script setup>

</script>

<style scoped>
body{
    height: 1000px;
    border: 5px solid black;
}
.position{
    border: 2px solid red;
    padding: 20px;
    width: 50%;
    height: 1000px;
    position: relative;
    margin: 100px;
    top: 100px;
    left: 50px;
}

#one{
    height: 100px;
    width: 100px;
    background-color: green;
    display: inline-block;
    position: relative;
    z-index: 1;

}
#two{
    height: 100px;
    width: 100px;
    background-color: blue;
    display: inline-block;
    position: relative;
    top: 50px;
    right: 50px;
    z-index: 2;
}
#three{
    height: 100px;
    width: 100px;
    background-color: black;
    display: inline-block;
    position: relative;
    top: 100px;
    right: 100px;
    z-index: 1;
}
</style>z