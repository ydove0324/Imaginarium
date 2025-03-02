<script setup>
// import page from '../mds/md.mdx';
</script>

<template>
  <div>
    <el-row justify="center">
      <h1 class="section-title">Dataset</h1>
    </el-row>

    <el-row justify="center">
      <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12">
        <el-container class="video-container">
          <el-image src="./carousel/dataset.png" fit="contain" />
        </el-container>
      </el-col>
    </el-row>

    <el-divider />

    <el-row justify="center">
      <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12">
        <page />
      </el-col>
    </el-row>

    <el-row justify="center">
      <h1 class="section-title">Application: Fine-grained 3D scene Edit</h1>
    </el-row>

    <el-row justify="center">
      <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12">
        <p style="text-align: justify;">
          Our method enables fine-grained editing of 3D scenes in the image domain through masks or natural language
          instructions.
        </p>
      </el-col>
    </el-row>

    <el-row justify="center">
      <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12">
        <el-container class="video-container">
          <el-image src="./carousel/application.png" fit="contain" />
        </el-container>
      </el-col>
    </el-row>

    <el-row justify="center">
      <h1 class="section-title">Comparison</h1>
    </el-row>

    <el-row justify="center">
      <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12">
        <el-container class="video-container">
          <el-image src="./carousel/comparison.png" fit="contain" />
        </el-container>
      </el-col>
    </el-row>

  </div>
</template>

<style scoped>
.video-container {
  margin: 20px 0px 0px 0px;
}

.section-title {
  margin-top: 40px;
}
</style>