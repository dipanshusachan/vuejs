<template>
    <div>
        <h1 class="h">Class and Style Bindings</h1>
        <h2 v-bind:style="{color:'red'}">Style Bindings</h2>
        <h2 v-bind:class="{display:show}">Class Binding with Object</h2>
        <h2 v-bind:class="[aclass]">Class Binding with Array</h2>
    </div>
</template>

<script>
export default {
    name:'ClassStyle',
    data() {
        return{
            show:true,
            aclass:'arrayClass'
        }
    },
}
</script>

<style>
.h{
    color: blue;
}
.display{
    background-color: rgb(74, 116, 57);
}
.arrayClass{
    background-color: rgba(43, 76, 82, 0.925);
}
</style>
