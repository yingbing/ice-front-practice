<template>
  <div id="app">
    {{ message }}
    <br/>
    <span v-bind:title="message_2">
      鼠标悬停几秒钟查看此处动态绑定的提示信息！
    </span>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      message: 'Welcome to Your Vue.js App',
      message_2: '页面加载于' + new Date()
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
</style>
