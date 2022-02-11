<template>
  <div id="app">
    <home></home>
  </div>
</template>
<script>
import home from "views/home.vue";
export default {
  // 数据
  data() {
    return {};
  },
  // 组件注册
  components: {
    home,
  },
  //钩子函数 组件被创建时候
  created() {},
  // 方法
  methods: {},
  // 计算属性
  computed: {},
};
</script>
<style>
@import "assets/css/base.css";
</style>
