<template>
  <div class="home">
    <template>
      <div class="note">
        <h4>Note:</h4>
        <p>如果无法直接点击磁力链接下载，请右键复制链接到下载器下载。</p>
        <p>
          If you can't directly click the MagnetURL to download, please
          right-click to copy the link to the downloader.
        </p>
      </div>
      <br />
      <el-table
        :data="resData"
        stripe
        style="
          width: 100%;
          box-shadow: 0 2px 4px rgba(0, 0, 0, 0.12), 0 0 6px rgba(0, 0, 0, 0.04);
        "
      >
        <el-table-column prop="title" label="Title"> </el-table-column>
        <el-table-column prop="hash" label="Hash" width="380">
        </el-table-column>
        <el-table-column label="MagnetURL" width="120">
          <template slot-scope="scope">
            <el-link :href="scope.row.murl" type="primary">Download</el-link>
          </template>
        </el-table-column>
      </el-table>
    </template>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  data() {
    return {
      resData: [
        {
          title: "【ASMR】被堕天使玩弄耳朵 / 足部按摩",
          hash: "A13E78B1829504250220A5D927FDCC545597302B",
          murl:
            "magnet:?xt=urn:btih:a13e78b1829504250220a5d927fdcc545597302b&dn=%e3%80%90ASMR%e3%80%91%e5%a0%95%e5%a4%a9%e4%bd%bf%e7%9a%84%e6%88%98%e4%ba%89%e8%b7%b5%e8%b8%8f.zip&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce&tr=udp%3a%2f%2ftracker.coppersurfer.tk%3a6969%2fannounce&tr=udp%3a%2f%2ftracker.leechers-paradise.org%3a6969%2fannounce&tr=udp%3a%2f%2fexplodie.org%3a6969%2fannounce&tr=http%3a%2f%2ft.nyaatracker.com%3a80%2fannounce&tr=http%3a%2f%2fsukebei.tracker.wf%3a8888%2fannounce&tr=http%3a%2f%2fnyaa.tracker.wf%3a7777%2fannounce",
        },
        {
          title: "猫窝首翻 / 纱雾本子",
          hash: "AE3223CE4AEE77496D01A314AD2BB746B8E0FD61",
          murl:
            "magnet:?xt=urn:btih:ae3223ce4aee77496d01a314ad2bb746b8e0fd61&dn=%e3%80%90%e7%8c%ab%e7%aa%9d%e9%a6%96%e7%bf%bb%e3%80%91%e7%ba%b1%e9%9b%be%e6%9c%ac%e5%ad%90.zip&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce&tr=udp%3a%2f%2ftracker.coppersurfer.tk%3a6969%2fannounce&tr=udp%3a%2f%2ftracker.leechers-paradise.org%3a6969%2fannounce&tr=udp%3a%2f%2fexplodie.org%3a6969%2fannounce&tr=http%3a%2f%2ft.nyaatracker.com%3a80%2fannounce&tr=http%3a%2f%2fsukebei.tracker.wf%3a8888%2fannounce&tr=http%3a%2f%2fnyaa.tracker.wf%3a7777%2fannounce",
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">

</style>