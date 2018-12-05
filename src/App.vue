<template>
  <div id="app" class="container">
    <img class="logo" src="./assets/logo.png">
    <todo-list></todo-list>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import TodoList from './components/TodoList'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TodoList
  }
}
</script>

<style>

* {
  box-sizing: border-box;
}

.container {
  width: 600px;
  margin: 0 auto;
}

#app {
  font-family: 'Open Sans', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  font-size: 18px;
}

.logo {
  display: block;
  margin: 20px auto;
  height: 75px;
}
</style>
