<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div>
      <router-link to="/">首页</router-link>|
      <router-link to="/Hi">Hi页面</router-link>|
      <router-link :to="{name:'Hi1',params:{username:'renfeiyan',id:98978}}">我是HI的子页面1</router-link>|
      <router-link to="Hi2">我是HI的子页面2</router-link>
    </div>
    <p>这是通过路由传递的路由名：{{$route.name}}</p>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
