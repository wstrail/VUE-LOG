<template>
  <p>{{ message }}</p>
  <p>{{ num + 2 }}</p>
  <p v-html="HTML"></p>
  <Helloworld />
  <ifdemo />
  <listdemo />
  <Arraylist />
  <Computerdemo />
  <Watchdemo />
  <Modeldemo />
</template>
<script setup>
import Arraylist from "./arraylist.vue";
import Computerdemo from "./computerdemo.vue";
import Modeldemo from "./modeldemo.vue";
import Watchdemo from "./watchdemo.vue";

/*export default {
  data() {
    return {
      message: "test",
      num: 10,
      HTML: "<p>text</p>",
    };
  },
};
import Helloworld from "./helloworld.vue";
import ifdemo from "./ifdemo.vue";
import listdemo from "./listdemo.vue";*/
</script>
