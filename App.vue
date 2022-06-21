<template>
<div id = "app">
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->

   <!-- <Pr data="Hii" msg=" I am Dipanshu"/> -->
   <!-- <Pr /> -->
  <!-- <Compmain /> -->
  <!-- <Normal/> -->
  <!-- <ClassStyle/> -->
  <!-- <DataBind/> -->
  <Form />
  <!-- <Befcreate /> -->
  <!-- <Mounted /> -->
  <!-- <EmployeeList /> -->
  <!-- <router-view></router-view> -->
  </div>
</template>

<script>

// import HelloWorld from './components/HelloWorld.vue'
// import Pr from './components/Pr.vue'
// import Compmain from './components/Compmain.vue'
// import Compmain from './components/Compmain.vue'
//  import Normal from './components/Normal.vue'
//  import ClassStyle from './components/ClassStyle.vue'
//  import DataBind from './components/DataBind.vue'
import Form from './components/Form.vue'
// import Befcreate from './components/Befcreate.vue'
// import Mounted from './components/Mounted.vue'
//  import EmployeeList from './components/EmployeeList.vue'



export default {
  name: 'App',
  components: {
    // HelloWorld,
    // Pr ,
    // Compmain
    // Normal,
    // ClassStyle
    // DataBind
    Form,
    // Befcreate
    // Mounted
    // EmployeeList
    

}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>


