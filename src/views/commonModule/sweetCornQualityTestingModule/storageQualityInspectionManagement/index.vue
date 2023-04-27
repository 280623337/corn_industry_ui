<template>
  <div>
    <BasicLayout>
      <template #wrapper>
        <el-card class="box-card">
        仓储环节质量检测管理
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
