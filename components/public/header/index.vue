<template>
  <div class="m-header">
    <el-row>
      <el-col>
        <top-bar/>
      </el-col>
    </el-row>
  </div>
</template>

<script>
import topBar from './topbar.vue'
export default {
  components:{
    topBar
  }
}
</script>

<style lang="stylus">
  @import "../../../assets/css/public/header/index.styl";
</style>
