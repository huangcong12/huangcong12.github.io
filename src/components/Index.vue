<template>
  <div class="hello">
    <h2>{{ msg }}</h2>
    <ul>
      <li>
        <a href="https://github.com/huangcong12">GitHub</a>
      </li>
      <li>
        <a href="https://github.com/huangcong12/huangcong12.github.io/issues">Blog</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Index",
  data() {
    return {
      msg: "来的都是客，欢迎呢"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
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
