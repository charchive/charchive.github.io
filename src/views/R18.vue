<template>
  <div class="r18">
    <template>
      <div class="note">
        <p>不可描述的领域w</p>
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
  name: "R18",
  components: {
    ResTable,
  },
  data() {
    return {
      resList: [
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