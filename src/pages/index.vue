<template>
  <div>
    123
    <Page :current="1" :total="100"></Page>
    <Steps :current="1">
        <Step title="已完成" content="这里是该步骤的描述信息"></Step>
        <Step title="进行中" content="这里是该步骤的描述信息"></Step>
        <Step title="待进行" content="这里是该步骤的描述信息"></Step>
        <Step title="待进行" content="这里是该步骤的描述信息"></Step>
    </Steps>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  created() {},
  mounted() {},
  methods: {}
};
</script>

<style>
</style>
