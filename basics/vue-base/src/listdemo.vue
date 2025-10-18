<template>
  <h3>列表渲染</h3>
  <p v-for="item in names">{{ item }}</p>
</template>
<script>
export default {
  data() {
    return {
      names: ["1", "2", "3", "4"],
    };
  },
};
</script>
