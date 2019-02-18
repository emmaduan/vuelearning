<template>
  <div id="app" class="ap">
    <img src="./assets/logo.png">
    <HelloWorld/>
    <login/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import login from './components/login.vue'

export default {
  name: 'App',
  components:{
    HelloWorld,
    login
  }
}
</script>

<style>
.ap{
  text-align: center;
  margin-top: 200px;
}
</style>
