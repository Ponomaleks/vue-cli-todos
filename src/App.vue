Vue.config.devtools = true;


<template>
  <div>
    <h1>Todo app</h1>
    <hr />
    <TodoList />
  </div>
</template>

<script>
import TodoList from '@/components/TodoList';

export default {
  name: 'App',

  components: {
    TodoList,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  color: #2c3e50;
  margin-top: 60px;
}
h1 {
  text-align: center;
}
</style>

