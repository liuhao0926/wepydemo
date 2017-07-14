<style lang="less">
</style>
<template>
  <view class="container">
   我是 PostList 页面
      <navigator url="/pages/post/detail" hover-class="navigator-hover">跳转到 post detail 页</navigator>
  </view>
</template>

<script>
  import wepy from 'wepy';
  import testMixin from '../../mixins/test';

  export default class List extends wepy.page {
    config = {
      navigationBarTitleText: 'PostList Page'
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
