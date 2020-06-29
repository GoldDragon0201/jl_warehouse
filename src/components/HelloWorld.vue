<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>我是主分支</p>
    <p>开发dev分支</p>
    <div>
        <p>dev内容</p>
    </div>
    <p>我是第二次提交内容</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
