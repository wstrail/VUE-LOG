<template>
  <h3>Parent</h3>
  <Child :title="message" demo="test" :age="age" :names="names" />
</template>
<script>
import Child from "./Child.vue";
export default {
  data() {
    return {
      message: "parent数据!",
      age: 20,
      names: ["iwen", "ime", "frank"],
    };
  },
  components: {
    Child,
  },
};
</script>
