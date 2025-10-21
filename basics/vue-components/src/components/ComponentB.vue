<template>
  <h3>ComponentB</h3>
  <p>{{ title }}</p>
</template>
<script>
export default {
  data() {
    return {};
  },
  props: { title: { type: String } },
};
</script>
