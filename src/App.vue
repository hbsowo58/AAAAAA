<template>
  <div id="app">
    <TodoHeader></TodoHeader>
    <TodoInput></TodoInput>
    <TodoList></TodoList>
    <TodoFooter></TodoFooter>
  </div>
</template>

<script>
import TodoFooterVue from "./components/TodoFooter.vue";
import TodoListVue from "./components/TodoList.vue";
import TodoInputVue from "./components/TodoInput.vue";
import TodoHeaderVue from "./components/TodoHeader.vue";
export default {
  components: {
    TodoHeader: TodoHeaderVue,
    TodoInput: TodoInputVue,
    TodoList: TodoListVue,
    TodoFooter: TodoFooterVue
  }
};
</script>

<style></style>
