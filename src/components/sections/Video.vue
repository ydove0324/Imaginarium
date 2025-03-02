<script setup>
</script>

<template>
  <div>
    <el-divider />

    <el-row justify="center">
      <!-- <h1 class="section-title">Teasor</h1> -->
    </el-row>

    <!-- 每个网站的视频的iframe可能不一致，最好在这里手动调整 -->
    <el-row justify="center">
      <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12">

        <!-- local -->
        <!-- <el-container class="video-container">
          <video controls muted preload playsinline>
            <source src="/video/video.mp4" type="video/mp4">
          </video>
        </el-container> -->

        <!-- bilibili -->
        <!-- <el-container class="video-container">
          <iframe src="//www.bilibili.com/blackboard/html5mobileplayer.html?bvid=BV1zw68YsEP9" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>
        </el-container> -->

        <!-- youtube -->
        <el-container class="video-container">
          <el-image src="./carousel/teasor.png" fit="contain" />
        </el-container>
      </el-col>
    </el-row>

    <el-row justify="center">
      <h1 class="section-title">Pipeline</h1>
    </el-row>

    <el-row justify="center">
      <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12">
        <el-container class="video-container">
          <el-image src="./carousel/pipeline.png" fit="contain" />
        </el-container>
      </el-col>
    </el-row>
  </div>
</template>

<style scoped>
.video-container {
  margin: 20px 0px 0px 0px;
}

iframe,
video {
  aspect-ratio: 16 / 9;
  width: 100%;
}

.section-title {
  margin-top: 40px;
  /* 添加标题的上边距 */
}
</style>