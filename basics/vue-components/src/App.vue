<template>
  <Header />
  <Main />
  <Aside />
  <Parent />
  <ComponentA />
  <Componentevent />
  <Body />
</template>
<script>
import Header from "./pages/Header.vue";
import Main from "./pages/Main.vue";
import Aside from "./pages/Aside.vue";
import Parent from "./components/Parent.vue";
import ComponentA from "./components/ComponentA.vue";
import Componentevent from "./components/Componentevent.vue";
import Body from "./components/body.vue";
export default {
  components: {
    Header,
    Main,
    Aside,
    Parent,
    ComponentA,
    Componentevent,
    Body,
  },
};
</script>
<style></style>
