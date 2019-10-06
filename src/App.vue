<template>
  <div id="app" class="container">
    <h1 class="title is-1">My Todo List</h1>
    <TodoList />
  </div>
</template>

<script>
import TodoList from "@/components/TodoList.vue";

export default {
  name: "app",
  components: {
    TodoList
  }
};
</script>

<style lang="scss">
.container {
  margin: 100px 60px 0 100px;
}
</style>
