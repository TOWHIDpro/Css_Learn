<template>
<div>
    <table>
        <caption>This is table</caption>
        <tr>
            <th>head1</th>
            <th>head2</th>
            <th>head3</th>
        </tr>
        <tr>
            <td>data1</td>
            <td>data2</td>
            <td>data3</td>
        </tr>
        <tr>
            <td>data1</td>
            <td>data2</td>
            <td>data3</td>
            <td></td>
        </tr>
    </table>
</div>
</template>

<script setup>

</script>

<style scoped>
caption{
    caption-side: bottom;
}
th{
    border: 1px solid black;
    height: 30px;
    
}
td{
    border: 1px solid black;
    height: 100px;
    width: 100px;
    vertical-align: bottom;
    text-align: right;
    
}
table{
    border: 1px solid black;
    border-collapse: separate;
    border-spacing: 15px;
    empty-cells: hide
    
    
}
</style>