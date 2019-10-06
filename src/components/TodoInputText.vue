<template>
  <div class="control has-icons-left has-icons-right">
    <input class="input is-medium" type="text" :value="value" placeholder="Enter your task" />
    <span class="icon is-left">
      <i class="fas fa-check"></i>
    </span>
  </div>
</template>

<script>
export default {
  props: ["value"]
};
</script>

<style>
</style>