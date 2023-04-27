<template>
  <div>
    <BasicLayout>
      <template #wrapper>
        <el-card class="box-card">
        多表页管理与表页汇总
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
