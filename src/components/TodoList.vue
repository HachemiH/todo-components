<template>
  <div>
    <TodoInputText />
  </div>
</template>

<script>
import TodoInputText from "@/components/TodoInputText.vue";
export default {
  components: {
    TodoInputText
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