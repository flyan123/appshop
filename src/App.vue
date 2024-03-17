<template>
  <div>
    <el-button type="primary" size="default" :icon="Plus">主要按钮</el-button>
    <Text/>
  </div>
</template>

<script setup lang="ts">
// 引入图标组件
import { Plus } from '@element-plus/icons-vue'
import Text from '@/components/text.vue'
</script>

<style scoped></style>
