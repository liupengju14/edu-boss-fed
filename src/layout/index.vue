<template>
    <el-container>
        <el-header></el-header>
        <el-main><slot></slot></el-main>
        <el-footer></el-footer>
    </el-container>
</template>
<style scoped>
.el-container{
    height:100%;
}
  .el-header, .el-footer {
    background-color: #B3C0D1;
    color: #333;
    text-align: center;
    line-height: 60px;
  }

  .el-main {
    background-color: #E9EEF3;
    color: #333;
    text-align: center;
    /* line-height: 160px; */
  }

  body > .el-container {
    margin-bottom: 40px;

  }
</style>
