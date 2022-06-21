<template>
<div>
    <h2>Some Features</h2>
    <h3 v-once>{{name}}</h3>
     <h3>{{name}}</h3>
    <h3>{{10+30}}</h3>
    <button v-on:click="updateText">Click Me</button>

    <!-- html props -->
    <p v-html="rowHtml"></p>

    <!-- disable button -->
    <button v-bind:disabled="disableBtn">Disable button</button>

</div>
</template>

<script>
export default {
    name:'Normal',
    data() {
        return {
            name : "Dip",

            // add html property
            rowHtml:"<h1>Adding the html Property</h1>"
,
            // disable button
            disableBtn:true
        }    
    },
    methods:{
        updateText(){
            this.name="Sac"
            // this.name=!this.name
        }
    }
}
</script>
