<template>
  <div>
    <BasicLayout>
      <template #wrapper>
        <el-card class="box-card">
        数据治理服务
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
