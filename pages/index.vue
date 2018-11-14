<template>
  <div class="page-index">
    <el-row>
      <el-col :span="24">
        <emenu/>
      </el-col>
    </el-row>
    <el-row >
      <el-col :span="24">
        <v-main/>
      </el-col>
    </el-row>
  </div>
</template>

<script>
import Emenu from '@/components/index/menu.vue'
import vMain from '@/components/index/main.vue'
export default {
  components: {
    Emenu,
    vMain
  }
}
</script>

