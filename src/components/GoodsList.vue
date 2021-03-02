<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    我是goodslist1<br/>
    我是goodslist2<br/>
    我是goodslist3：{{str}}<br/>
  </div>
</template>

<script>
export default {
  name: 'GoodsList',
  props: {
    msg: String,
    str:"郝刚"
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
