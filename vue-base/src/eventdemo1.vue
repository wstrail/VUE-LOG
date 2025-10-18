<template>
  <h3>内联</h3>
  <button v-on:click="addCount">Add</button>
  <p>{{ count }}</p>
</template>
<script>
export default {
  data() {
    return { count: 0 };
  },
  methods: {
    addCount(e) {
      e.target.innerHTML = "add" + this.count;
      this.count++;
    },
  },
};
</script>
