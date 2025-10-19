<template>
  <h3>数组变化侦听</h3>
  <button @click="add">添加数据</button>
  <ul>
    <li v-for="(item, index) of names" :key="index">{{ item }}</li>
  </ul>
</template>
<script>
export default {
  data() {
    return {
      names: ["iwen", "ime", "frank"],
    };
  },
  methods: {
    add() {
      this.names.push("sakura");
    },
  },
};
</script>
