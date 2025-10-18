<template>
  <h3>条件渲染</h3>
  <div v-if="flag">test</div>
  <div v-else>this one</div>
</template>
<script>
export default {
  data() {
    return {
      flag: false,
    };
  },
};
</script>
