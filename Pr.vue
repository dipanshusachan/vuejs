<template>
<div>
    <h1>Your Good Name</h1>
    <h2>{{data}}</h2>
    <h3>{{msg}}</h3> 
    <button v-on:click="hello('How are You...?')">Click Here</button>
   
   <!-- rendering -->
    <h3 v-if="show">Conditional Rendering in vue js</h3>
    <h3 v-else>Conditional Rendering else block</h3>
    <button v-on:click="display">Toggle Element</button>

    <!-- for loop -->
    <table border="1px">
        <tr>
            <th>Id</th>
            <th>Name</th>
            <th>Email</th>
        </tr>

        <tr v-for="user in users" :key="user.id">
            <td>{{user.id}}</td>
            <td>{{user.Name}}</td>
            <td>{{user.email}}</td>
        </tr>
    </table>

</div>
</template>

<script>
    export default {
        name :"Pr",
        props:{
          data:String,
          msg:String
        },
        methods:{
            hello(a){
                alert(a)
         } },
            // for rendering (if else condition)
            data(){
                return {show:true}
   
        },

        // for toggle Element
        methods:{
            display(){
                this.show=!this.show
            }
        },
    

        // for loop
        data(){
            return{
                users:
                [
                    {id:1, Name:'wew', email:'wew@gmail.com'},
                    {id:2, Name:'sew', email:'sew@gmail.com'},
                    {id:3, Name:'pew', email:'pew@gmail.com'}

                
                ]
            }
        }
    }
</script>
