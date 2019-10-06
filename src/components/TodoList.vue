<template>
  <div>
    <TodoInputText v-model="newTodoText" />
    <TodoListItem :todos="todos" />
  </div>
</template>

<script>
import TodoInputText from "@/components/TodoInputText.vue";
import TodoListItem from "@/components/TodoListItem.vue";

export default {
  components: {
    TodoInputText,
    TodoListItem
  },
  data() {
    return {
      newTodoText: "toto",
      todos: ["Tomate", "Lait", "Beurre"]
    };
  }
};
</script>

<style>
</style>