<template>
  <h3>表单输入与绑定</h3>
  <form><input type="text" v-model="message"></input></form>
    <p>{{ message }}</p>
</template>
<script>
export default {
  data() {
    return {
        message:""
    };
  },
};
</script>
