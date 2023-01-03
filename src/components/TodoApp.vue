<template>
  <div class="todo-app">
    <h1>To Do List</h1>
    <todo-form />
    <todo-list />
  </div>
</template>

<script>
import { defineComponent } from "vue";
import TodoForm from "./TodoForm.vue";
import TodoList from "./TodoList.vue";
export default defineComponent({
  components: { TodoForm, TodoList },
  setup() {
    return {};
  },
});
</script>
<style scoped>
.todo-app {
  position: relative;
  padding: 5vh;
  min-height: 100vh;
  width: 80vw;
  background-color: #f7f9fc;
  left: 10vw !important;
}
</style>