<template>
  <Header />
  <Main />
  <Aside />
  <Parent />
</template>
<script>
import Header from "./pages/Header.vue";
import Main from "./pages/Main.vue";
import Aside from "./pages/Aside.vue";
import Parent from "./components/parent.vue";

export default {
  components: {
    Header,
    Main,
    Aside,
    Parent,
  },
};
</script>
<style></style>
