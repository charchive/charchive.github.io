<template>
  <el-menu
    class="top-bar"
    mode="horizontal"
  >
    <el-menu-group class="logo">
        <img height="55px" src="@/assets/logo.svg">
    </el-menu-group>
  </el-menu>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.top-bar {
  margin-bottom: 20px;
}
.logo {
    outline: none;
}
</style>
