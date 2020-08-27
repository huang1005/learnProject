<template>
  <div>
    <input type="text" v-model="values">
    <test :values="values"></test>
  </div>
</template>

<script>
import test from "./test";
export default {
  name: 'helloword',
  components: {
    test
  },
  data() {
    return {
      values: ''
    };
  }
};
</script>

<style scoped lang='scss' rel='stylesheet/scss'>
</style>
