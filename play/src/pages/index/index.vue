<script setup lang="ts">
import { ref } from 'vue'
import TnSuspendButton from '../../packages/src/index.vue'

const message = ref<string>('欢迎开发TuniaoUI v3 uniapp 插件')
</script>

<template>
  <view class="content">
    <view class="message">{{ message }}</view>
    <TnSuspendButton icon="logo-tuniao" shape="circle" />
  </view>
</template>

<style lang="scss" scoped>
.content {
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

  .message {
    font-size: 50rpx;
  }
}
</style>
