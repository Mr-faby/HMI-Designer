<template>
  <div class="text-comp-config comp-item-config">
    <div class="inline">
      <label for="text">文本：</label>
      <input type="text" style="width:100px" name="text" v-model="currentCompData['data_source']['text']" />
    </div>
  </div>
</template>

<script>
export default {
  data: () => {
    return {};
  },
  props: ["currentCompData"],
  mounted() {
  }
};
</script>

.<style lang="scss" scoped>
</style>