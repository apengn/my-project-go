<template>
  <div class="hello">
    <ul>
      <li>
        <a href="#">
          首页
        </a>
      </li>

      <li>
        <a
          href="https://github.com/vuejs/awesome-vue"
          target="_blank"
        >
          Golang新闻
        </a>
      </li>
      <li>
        <a
          href="http://vuex.vuejs.org/"
          target="_blank"
        >
          Golang论坛
        </a>
      </li>
      <li>
        <a
          href="http://vue-loader.vuejs.org/"
          target="_blank"
        >
          Golang基础教程
        </a>
      </li>
      <li>
        <a
          href="https://github.com/vuejs/awesome-vue"
          target="_blank"
        >
          Golang高级教程
        </a>

      </li>
    </ul>

    <div class="class_header">
      <img
        src="https://ss2.baidu.com/6ONYsjip0QIZ8tyhnq/it/u=4071853574,2383726230&fm=58&s=C983E61697236F011AEB71D6020010BA"/>

      <div class="class_header_right">
        <div class="class_header_right_content">
          <input/>
          <button> search</button>
          <br/>
          <span><a href="">热搜</a></span>
          <span><a href="">scrapy</a></span>
          <span><a href="">urllib2</a></span>
          <span><a href="">yield</a></span>
          <span><a href="">python</a></span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data() {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .hello {
    text-align: center;
  }

  h1, h2 {
    font-weight: normal;
  }

  ul {
    list-style-type: none;
    width: 75%;
    white-space: nowrap;
    margin: auto;
    padding: 10px 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
    font-size: 40px;
    font-weight: 100;
    text-decoration: none;
    background: aquamarine;
  }

  a:hover {
    background: #40ff81;
  }

  .class_header {
    display: inline-block;
    width: 58%;
    margin: 0px auto;
  }

  .class_header img {
    width: 20%;
    height: 150px;
    float: left;
  }

  .class_header_right {
    background: aqua;
    height: 150px;
    width: auto;
    display: flex;
    justify-content: center;
    justify-items: center;
  }

  .class_header_right_content {
    float: right;
  }

  span
  a {
    font-size: 10pt;
  }
</style>
