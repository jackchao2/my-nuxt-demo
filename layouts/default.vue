<template>
  <div class="common-layout">
    <el-container>
      <el-header>Header</el-header>
      <el-main>
        <slot />
      </el-main>
      <el-footer>Footer</el-footer>
    </el-container>
  </div>
</template>
<style lang="scss" scoped>
.common-layout {
  .el-container {
    height: calc(100vh);
    .el-header {
      background-color: #ccccff;
    }
    .el-footer {
      background-color: #ccffff;
    }
    .el-main {
      background-color: #ffcccc;
    }
  }
}
</style>