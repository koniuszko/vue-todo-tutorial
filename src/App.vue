<template>
  <div>
    <h1>Todo app</h1>
    <TodoApp />
  </div>
</template>

<script>
import Todo from "./components/TodoApp.vue";

export default {
  components: {
    TodoApp: Todo,
  },
};
</script>
