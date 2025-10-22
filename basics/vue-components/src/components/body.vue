<template>
  <h3>Main</h3>
  <p>搜索内容为{{ search }}</p>
  <SearchComponent @searchevent="getsearch" />
</template>
<script>
import SearchComponent from "./searchComponent.vue";

export default {
  data() {
    return { search: "" };
  },
  components: { SearchComponent },
  methods: {
    getsearch(data) {
      this.search = data;
    },
  },
};
</script>
