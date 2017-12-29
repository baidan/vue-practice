<template>
  <div class="hello">
    <h1>{{ msg}}</h1>
    <h1>{{ msg}}</h1>
    <pre>{{$data}}</pre>
    <input v-bind:data-test="msg">
    <input v-model="msg">
  </div>
</template>

<script>
export default {
  name: 'demo',
  data () {
    return {
      msg: '操作成功',
      code:'0000',
      data:[{
        key:'ddd'
      }]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<!-- 添加“作用域”属性，仅将CSS限制为该组件 -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
