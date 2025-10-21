<template>
  <h3>ComponentB</h3>
  <p>{{ title }}</p>
  <p>{{ age }}</p>
  <p>{{ names }}</p>
</template>
<script>
export default {
  data() {
    return {};
  },
  props: {
    title: { type: String },
    age: { type: Number, default: 0 },
    names: {
      type: Array,
      default() {
        return "空";
      },
    },
  },
};
</script>
注:父级传递过来的元素
