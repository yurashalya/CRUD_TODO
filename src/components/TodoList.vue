<template>
    <div>
        <input type="text" class="todo-inp" 
        placeholder="What needs to be done"
        v-model="newTodo"
        >
        Todo List goes here
    </div>
</template>

<script>
export default {
  name: 'todo-list',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>


<style lang="scss">


.todo-inp {
    width: 100%;
    padding: 10px 18px;
    font-size: 18px;
    margin-bottom: 16px;

    &:focus {
      outline: 0;
    }
  }

</style>
