<template>
  <el-form-item :label="i18nt('designer.setting.validationHint')">
    <el-input type="text" v-model="optionModel.validationHint" :placeholder="i18nt('designer.setting.validationHintPlaceholder')"></el-input>
  </el-form-item>
</template>

<script>
  import i18n from "@/utils/i18n"

  export default {
    name: "validationHint-editor",
    mixins: [i18n],
    props: {
      designer: Object,
      selectedWidget: Object,
      optionModel: Object,
    },
  }
</script>

<style scoped>

</style>
