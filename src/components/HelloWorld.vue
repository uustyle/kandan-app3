<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>



    <nav class="navbar navbar-dark fixed-top bg-dark flex-md-nowrap p-0 shadow">
      <a class="navbar-brand col-sm-3 col-md-2 mr-0" href="#">NMS</a>
      <input class="form-control form-control-dark col-md-6 w-100" type="text" id="topInput" disabled style="background-color: #484D53">
      <div class="bar col-md-2">
        <span href="#">test</span>
      </div>
      <div class="bar col-md-1" v-show="false">

        <a href="../../static/manual.pdf" target="_blank">
          <span id="span" data-feather="book-open"></span>マニュアル</a>
      </div>
      <div class="bar col-md-1">
        <a href="#" @click=logout()>ログアウト</a>
      </div>
    </nav>


<div>
  <b-alert show variant="primary">Primary Alert</b-alert>
  <b-alert show variant="secondary">Secondary Alert</b-alert>
  <b-alert show variant="success">Success Alert</b-alert>
  <b-alert show variant="danger">Danger Alert</b-alert>
  <b-alert show variant="warning">Warning Alert</b-alert>
  <b-alert show variant="info">Info Alert</b-alert>
  <b-alert show variant="light">Light Alert</b-alert>
  <b-alert show variant="dark">Dark Alert</b-alert>
</div>


    <ul>
      <li>
        <a
          href="https://vuejs.org"
          target="_blank"
        >
          Core Docs
        </a>
      </li>
      <li>
        <a
          href="https://forum.vuejs.org"
          target="_blank"
        >
          Forum
        </a>
      </li>
      <li>
        <a
          href="https://chat.vuejs.org"
          target="_blank"
        >
          Community Chat
        </a>
      </li>
      <li>
        <a
          href="https://twitter.com/vuejs"
          target="_blank"
        >
          Twitter
        </a>
      </li>
      <br>
      <li>
        <a
          href="http://vuejs-templates.github.io/webpack/"
          target="_blank"
        >
          Docs for This Template
        </a>
      </li>
    </ul>
    <h2>Ecosystem</h2>
    <ul>
      <li>
        <a
          href="http://router.vuejs.org/"
          target="_blank"
        >
          vue-router
        </a>
      </li>
      <li>
        <a
          href="http://vuex.vuejs.org/"
          target="_blank"
        >
          vuex
        </a>
      </li>
      <li>
        <a
          href="http://vue-loader.vuejs.org/"
          target="_blank"
        >
          vue-loader
        </a>
      </li>
      <li>
        <a
          href="https://github.com/vuejs/awesome-vue"
          target="_blank"
        >
          awesome-vue
        </a>
      </li>
    </ul>
  </div>
</template>

<style  src="../../static/css/bootstrap.min.css" />

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
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
