<template>
  <div>
    <TodoInputText v-model="newTodoText" @keydown.enter="addTodo" />
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
      newTodoText: "",
      todos: ["Tomate", "Lait", "Beurre"]
    };
  },
  methods: {
    addTodo() {
      alert("test");
    }
  }
};
</script>

<style>
</style>