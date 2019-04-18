<template>
  <div class="box">
    <div class="box-content">
      <ul>
        <li>
          <a class="title" href="https://github.com/huangcong12">文1</a>
        </li>
        <li>
          <a class="title" href="https://github.com/huangcong12">文2</a>
        </li>
        <li>
          <a class="title" href="https://github.com/huangcong12">文3</a>
        </li>
        <li>
          <a class="title" href="https://github.com/huangcong12">文4</a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "list",
  data() {
    return {
      msg: "列表页"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.box {
  display: flex;
  justify-content: center;
}
.box-content {
  flex-direction: row;
  width: 80%;
  border: 1px solid #ddd;
  border-top-right-radius: 4px;
  border-top-left-radius: 4px;
}
ul {
  padding: 0px;
  margin: 0px;
}
li {
  align-items: center;
  height: 3.5rem;
  list-style-type: none;
  text-align: left;
}
li a {
  display: block;
  text-decoration: none;
  color: #428bca;
  font-size: 1.6rem;
  width: 100%;
}
li:hover {
  background-color: #eee;
  font-size: 100%;
}
</style>
