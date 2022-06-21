<template>
    <div>
        <h1><u>This is Main File</u></h1>
        <Compchild/>
        <Products/>
    </div>
</template>

<script>
import Compchild from './Compchild'
import Products from './Products'
export default {
    name:'Compmain',
    components:{
        Compchild,
        Products,
    }
}
</script>

<style>
    div{
            background-color: #cedae5;
            height: 500px;
            margin: 20px;
}
   
</style>
