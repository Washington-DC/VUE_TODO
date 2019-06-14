<template>
  <div class="list-item editingClass">
    <label class="checkbox">
      <input type="checkbox" v-model="item.checked">
      <span class="checkbox-custom"></span>
    </label>

    <input type="text" v-model="item.text" placeholder="写点什么...">
    <a class="delete-item">
      <span class="icon-trash"></span>
    </a>
  </div>
</template>

<script>
export default {
  name: "",
  data() {
    return {};
  },
  props: ["item"]
};
</script>

<style lang="less" scoped>
@import "../common/style/list-items.less";
</style>