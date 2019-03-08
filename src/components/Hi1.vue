<template>
  <div>
    <h4>{{message}}</h4>
    <p>{{author}}--{{$route.params.username}}---id:{{$route.params.id}}</p>
  </div>
<!--//id:{{$route.params.id}}这种方法在实际开发中用的比较多-->
</template>

<script>
  export default {
    name: "Hi1",
    data(){
      return{
        message:"我是Hi1",
        author:"我喜欢发现美食"
      }
    }
  }
</script>

<style scoped>

</style>
