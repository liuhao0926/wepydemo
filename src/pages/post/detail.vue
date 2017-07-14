<style lang="less">
</style>
<template>
  <view class="container">
   我是 PostDetail 页面
  </view>
</template>

<script>
  import wepy from 'wepy';
  import testMixin from '../../mixins/test';

  export default class Detail extends wepy.page {
    config = {
      navigationBarTitleText: 'PostDetail Page'
    }
    components = {
    }
    mixins = [testMixin]

    data = {
    }

    methods = {

    }

    events = {
    }

    onLoad() {
      // let self = this;
    }
  }
</script>
