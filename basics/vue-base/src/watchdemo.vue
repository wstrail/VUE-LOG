<template>
  <p>{{ message }}</p>
  <button @click="updateHandle">更新</button>
</template>

<script>
export default {
  data() {
    return {
      message: "Hello",
    };
  },
  methods: {
    updateHandle() {
      this.message = "World";
    },
  },
  watch: {
    message(newvalue, oldvalue) {
      console.log(newvalue, oldvalue);
    },
  },
};
</script>
