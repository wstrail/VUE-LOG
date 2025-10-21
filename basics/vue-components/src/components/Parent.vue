<template>
  <h3>Parent</h3>
  <Child :title="message" demo="test" :age="age" />
</template>
<script>
import Child from "./Child.vue";
export default {
  data() {
    return {
      message: "parent数据!",
      age: 20,
    };
  },
  components: {
    Child,
  },
};
</script>
