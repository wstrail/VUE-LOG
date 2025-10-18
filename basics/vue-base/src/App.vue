<template>
  <p>{{ message }}</p>
  <p>{{ num + 2 }}</p>
  <p v-html="HTML"></p>
  <Helloworld />
  <ifdemo />
  <listdemo />
</template>
<script setup>
/*export default {
  data() {
    return {
      message: "test",
      num: 10,
      HTML: "<p>text</p>",
    };
  },
};*/
import Helloworld from "./helloworld.vue";
import ifdemo from "./ifdemo.vue";
import listdemo from "./listdemo.vue";
</script>
