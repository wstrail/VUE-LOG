<template>
  <h3>ComponentA</h3>
  <ComponentB :title="title" />
</template>
<script>
import ComponentB from "./ComponentB.vue";
export default {
  data() {
    return {
      title: "测试标题",
    };
  },
  components: { ComponentB },
};
</script>
