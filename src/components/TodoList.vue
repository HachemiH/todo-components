<template>
  <div>
    <TodoInputText />
    <TodoListItem />
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
      todos: ["Tomate", "Lait", "Beurre"]
    };
  }
};
</script>

<style>
</style>