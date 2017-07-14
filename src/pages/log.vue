<style lang="less">
</style>
<template>
  <view class="container">
   我是log页面
  <navigator url="/pages/index" hover-class="navigator-hover">跳转到组件demo页面</navigator>
  <view>
    <!-- <rich-text nodes="{{nodes}}"></rich-text> -->
  </view>
  </view>
</template>

<script>
  import wepy from 'wepy';
  import testMixin from '../mixins/test';

  export default class Log extends wepy.page {
    config = {
      navigationBarTitleText: 'log page'
    }
    components = {
    }
    mixins = [testMixin]

    data = {
      nodes: [{
        name: 'div',
        attrs: {
          class: 'div_class',
          style: 'line-height: 60px; color: red;'
        },
        children: [{
          type: 'text',
          text: 'Hello&nbsp;World!'
        }]
      }]
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
