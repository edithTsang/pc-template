<template>
  <div>
    <Breadcrumb :breadcrumb="breadcrumb" />
    <div>邮箱修改</div>
  </div>
</template>
<script>
import Breadcrumb from '../../../components/Member/Breadcrumb'
export default {
  components: { Breadcrumb },
  data() {
    return {
      breadcrumb: {
        text: '个人中心',
        text2: '账号管理',
        text3: '邮箱修改'
      }
    }
  }
}
</script>

