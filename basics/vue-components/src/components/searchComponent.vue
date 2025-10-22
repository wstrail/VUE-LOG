<template><input type="text" v-model="search" /></template>
<script>
export default {
  data() {
    return {
      search: "",
    };
  },
  watch: {
    search(newValue, oldValue) {
      this.$emit("searchevent", newValue);
    },
  },
};
</script>
