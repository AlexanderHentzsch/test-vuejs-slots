<template>
  <div style="display: flex">
    <div>
      <slot name="left"></slot>
    </div>
    <div style="flex-grow: 1">
      <slot></slot>
    </div>
    <div>
      <slot name="right"></slot>
    </div>
  </div>
</template>

<script>
export default {
  name: "gridAutoMiddle"
};
</script>
<style scoped>
div > div {
  padding: 0 8px;
}
</style>

