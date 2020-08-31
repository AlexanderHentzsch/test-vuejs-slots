<template>
  <div style="display: flex">
    <div style="flex-grow: 1">
      <p style="margin: 0">{{content}}</p>
    </div>
    <div>
      <i class="far fa-edit"></i>
    </div>
  </div>
</template>

<script>
export default {
  name: "todoElement",
  data: function() {
    return {
      content: "Dies ist ein ToDo Eintrag"
    };
  }
};
</script>
