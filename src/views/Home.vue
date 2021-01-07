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
      <ResTable :resData="resList"/>
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
  data() {
    return {
      resList: [
        {
          title: "【ASMR】被堕天使玩弄耳朵 / 足部按摩",
          hash: "A13E78B1829504250220A5D927FDCC545597302B",
          murl:
            "magnet:?xt=urn:btih:a13e78b1829504250220a5d927fdcc545597302b&dn=%e3%80%90ASMR%e3%80%91%e5%a0%95%e5%a4%a9%e4%bd%bf%e7%9a%84%e6%88%98%e4%ba%89%e8%b7%b5%e8%b8%8f.zip&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce&tr=udp%3a%2f%2ftracker.coppersurfer.tk%3a6969%2fannounce&tr=udp%3a%2f%2ftracker.leechers-paradise.org%3a6969%2fannounce&tr=udp%3a%2f%2fexplodie.org%3a6969%2fannounce&tr=http%3a%2f%2ft.nyaatracker.com%3a80%2fannounce&tr=http%3a%2f%2fsukebei.tracker.wf%3a8888%2fannounce&tr=http%3a%2f%2fnyaa.tracker.wf%3a7777%2fannounce",
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
</style>