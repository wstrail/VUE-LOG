<template>
  <h3>组件事件</h3>
  <ComponenteventChild @someEvent="getHandle" />
  <p>父元素：{{ message }}</p>
</template>
<script>
import ComponenteventChild from "./ComponenteventChild.vue";
export default {
  data() {
    return {
      message: "",
    };
  },
  components: {
    ComponenteventChild,
  },
  methods: {
    getHandle(data) {
      this.message = data;
    },
  },
};
</script>
