<template>
  <div class="hello">
    <div class="holder">
      <input type="text">
    </div>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data() {
      return {
        skills: [
          {'skill': 'java'},
          { 'skill': 'python' }
        ],
        numbersList:[1,2,3,4,5,6],
        animals:{
          dog :'wangwang',
          panda :'wuwu',
          woof :'aooooooo'
        }
      }
    }
  }

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

</style>
