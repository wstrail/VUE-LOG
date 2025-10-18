<template>
  <h3>key属性</h3>
  <p v-for="(item, index) in names" :key="index">{{ item }}</p>
</template>
<script>
import { ssrImportMetaKey } from "vite/module-runner";

export default {
  data() {
    return {
      names: ["a", "b", "c"],
    };
  },
};
</script>
