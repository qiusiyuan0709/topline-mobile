<!-- 组件说明 -->
<template>
  <div id="app">
    <van-button type="default">默认按钮</van-button>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
    <!-- <van-radio-group v-model="radio">
      <van-radio name="1">单选框 1</van-radio>
      <van-radio name="2">单选框 2</van-radio>
    </van-radio-group> -->
    <router-view />
  </div>
</template>
<script>
// import x from ''
export default {
  name: 'App',
  components: {
  },
  data () {
    return {
      radio: 1
    }
  },
  computed: {
  },
  methods: {

  }
}
</script>

<style lang='less' scoped>
//@import url()
</style>
