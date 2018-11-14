<template>
  <el-row
    :gutter="0"
    class="m-header">
    <el-col :span="12">
      <user/>
    </el-col>
    <el-col :span="12">
      <navbar/>
    </el-col>
  </el-row>
</template>

<script>
import User from './user.vue'
import Navbar from './nav.vue'
export default {
  components:{
    User,
    Navbar
  }
}
</script>

<style lang="stylus">
  @import "../../../assets/css/public/layout.styl";
</style>
