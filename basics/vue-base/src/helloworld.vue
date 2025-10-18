<template>
  <div :class="msg" v-bind="object">测试</div>
  <button :disabled="button">button</button>
</template>
<script>
export default {
  data() {
    return {
      msg: "active",
      id: "appid",
      button: false,
      object: { msg: "active", id: "appid" },
    };
  },
};
</script>
<style>
.active {
  color: red;
  font-size: 30px;
}
</style>
