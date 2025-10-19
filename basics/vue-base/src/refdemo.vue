<template>
  <div ref="container" class="container">{{ content }}</div>
  <button @click="getElementHandle">获取元素</button>
</template>
<script>
export default {
  data() {
    return { content: "内容" };
  },
  methods: {
    getElementHandle() {
      console.log((this.$refs.container.innerHTML = "changed"));
    },
  },
};
</script>
