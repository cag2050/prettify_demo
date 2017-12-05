<template lang='pug'>
#app
    div 路由列表：
    a(href='/') Prettify
    <br/>
    router-link(to='/hello') hello
    div ----下面是内容-----
    <router-view/>
</template>

<script>
export default {
    name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
li.L0, li.L1, li.L2, li.L3, li.L5, li.L6, li.L7, li.L8, li.L9 {
 list-style-type: decimal !important
}
</style>
