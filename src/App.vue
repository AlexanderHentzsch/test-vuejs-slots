<template>
  <div id="app">
    <h1>Test it</h1>
    <todoElement/>
    <grid-auto-middle>
      <template v-slot:left>
        <span>+</span>
        <span>-</span>
      </template>Mittlerer Text
      <template v-slot:right>Right</template>
    </grid-auto-middle>
  </div>
</template>

<script>
import todoElement from "./components/todo-element.vue";
import gridAutoMiddle from "./components/grids/grid-auto-middle.vue";

export default {
  name: "App",
  components: { todoElement, gridAutoMiddle }
};
</script>

<style scoped>
</style>
