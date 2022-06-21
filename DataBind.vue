<template>
    <div>
        <h1>Binding the Data</h1>
        <h1>{{message}}</h1>
        <input type="text" v-model="message">

        <h2 style="white-space:pre-line">{{message}}</h2>
        <textarea name="text"  v-model="message"></textarea>

    </div>
</template>

<script>
export default {
    name:'DataBind',
    data(){
        return{
            message:'Hello'
        }
    }
}
</script>
