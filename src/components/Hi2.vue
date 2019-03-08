<template>
  <div>
    <h4>{{message}}</h4>
    <p>{{author}}</p>
  </div>

</template>

<script>
  export default {
    name: "Hi2",
    data(){
      return{
        message:"我是Hi2",
        author:"我喜欢玩游戏"
      }
    }
  }
</script>

<style scoped>

</style>
