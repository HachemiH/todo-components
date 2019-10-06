<template>
  <div class="control has-icons-left has-icons-right">
    <input
      class="input is-medium"
      type="text"
      placeholder="Enter your task"
      :value="value"
      v-on="listeners"
    />
    <span class="icon is-left">
      <i class="fas fa-check"></i>
    </span>
  </div>
</template>

<script>
export default {
  props: ["value"],
  computed: {
    listeners() {
      return {
        // Pass all component listeners directly to input
        ...this.$listeners,
        // Override input listener to work with v-model
        input: event => this.$emit("input", event.target.value)
      };
    }
  }
};
</script>

<style>
</style>