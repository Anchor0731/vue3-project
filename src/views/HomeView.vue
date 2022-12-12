<template>
  <div>
    <div>vue3 + vite project</div>
    <div>
      <el-button>el按钮1</el-button>
      <el-button type="danger" @click="dangerClick">点击弹出警告提示</el-button>
    </div>

    <son-comp />
    <use-mouse />
  </div>
</template>

<script setup>
const dangerClick = () => {
  ElMessage.error("这是一个错误提示");
};
</script>

<style lang="scss" scoped></style>
