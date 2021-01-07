<template>
  <div class="home">
    <template>
      <div class="note">
        <h4>Note:</h4>
        <p>如果无法直接点击磁力链接下载，请右键复制链接到下载器下载</p>
        <p>
          请尽可能不要使用迅雷进行下载，我们推荐开源、无广告的 <el-link href="https://github.com/c0re100/qBittorrent-Enhanced-Edition/releases" type="primary" target="_blank">qBittorrent</el-link> 下载器。
        </p>
      </div>
      <br />
      <ResTable :resData="this.$store.state.resList"/>
    </template>
  </div>
</template>

<script>
import ResTable from '../components/ResTable.vue';
// @ is an alias to /src

export default {
  name: "Home",
  components: {
    ResTable,
  },
};
</script>

<style scoped lang="scss">
</style>