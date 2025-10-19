<template>
  <h3>{{ test.name }}</h3>
  <p>{{ content }}</p>
</template>
<script>
export default {
  data() {
    return {
      test: {
        name: "Text",
        content: ["a", "b", "c"],
      },
    };
  },
  computed: {
    content() {
      return this.test.content.length > 0 ? "yes" : "no";
    },
  },
};
</script>
