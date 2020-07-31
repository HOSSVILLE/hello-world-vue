<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/MULOGO.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  <div>
   <label for="firstName">First Name: </label>
   <input placeholder="Type here" type="text" v-model="firstName" id="firstName">
  </div>
  </div>
 </template>
<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
