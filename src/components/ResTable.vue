<template>
  <el-table
    :data="resData"
    stripe
    border
    style="
      width: 100%;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.12), 0 0 6px rgba(0, 0, 0, 0.04);
    "
  >
    <el-table-column prop="title" label="Title"> </el-table-column>
    <el-table-column prop="hash" label="Hash"> </el-table-column>
    <el-table-column label="MagnetURL" width="110">
      <template slot-scope="scope">
        <el-link :href="scope.row.murl" type="primary">Download</el-link>
      </template>
    </el-table-column>
  </el-table>
</template>

<script>
export default {
  name: "ResTable",
  props: {
    resData: {
      type: Array,
      default: function () {
        return [
          {
            title: "",
            hash: "",
            murl:
              "",
          },
        ];
      },
    },
  },
};
</script>

<style scoped lang="scss">
</style>
