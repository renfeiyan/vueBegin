<template>
    <div>
      <h4>{{message}}</h4>
      <p>{{author}}</p>
      <router-view></router-view>
    </div>

</template>

<script>
    export default {
        name: "Hi",
      data(){
          return{
            message:"这是Hi页面",
            author:"我超爱学习 不能停"
          }
      }
    }
</script>

<style scoped>

</style>
