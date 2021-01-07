<template>
  <div class="r18">
    <template>
      <div class="note">
        <p>不可描述的领域w</p>
      </div>
      <br />
      <ResTable :resData="this.$store.state.resListR18"/>
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
};
</script>

<style scoped lang="scss">
</style>