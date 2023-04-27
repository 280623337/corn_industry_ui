<template>
  <div>
    <BasicLayout>
      <template #wrapper>
        <el-card class="box-card">
        农业预警事件展示和分析
        </el-card>
      </template>
    </BasicLayout>
  </div>
</template>

<script>
import { addSysJob, delSysJob, getSysJob, listSysJob, updateSysJob, removeJob, startJob } from '@/api/job/sys-job'

export default {
  name: 'SysJobManage',
  components: {

  },
  data() {
    return {
    }
  },
  created() {
    
  },
  methods: {
  }
}
</script>
