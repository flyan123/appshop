<template>
  <div>
    <el-button type="primary" size="default" :icon="Plus">主要按钮</el-button>
    <Text />
    <h1>SVG测试</h1>
    <!-- 测试SVG图标使用 -->
    <!-- svg：图标外层容器节点，内部需要与use标签结合使用 -->
    <svg>
      <!-- xlink:href执行用哪一个图标 -->
      <use xlink:href="#icon-phone"></use>
    </svg>
  </div>
</template>

<script setup lang="ts">
// 引入图标组件
import { Plus } from '@element-plus/icons-vue'
import Text from '@/components/text.vue'
</script>

<style scoped></style>
