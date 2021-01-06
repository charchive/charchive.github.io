<template>
  <el-menu class="top-bar" mode="horizontal" router :default-active="$route.path">
    <img class="logo" height="55px" src="@/assets/logo.svg" />

    <el-menu-item class="dock-right" index="/about">About</el-menu-item>
    <el-menu-item class="dock-right" index="/">Home</el-menu-item>
  </el-menu>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style scoped lang="scss">
.top-bar {
  margin-bottom: 20px;
}
.logo {
  outline: none;
}
.el-menu--horizontal > .el-menu-item.dock-right {
  float: right;
}
</style>
