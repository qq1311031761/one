<template>
  <div>
    <h3>MemberContainer</h3>
  </div>
</template>

<script>
import { Toast } from 'mint-ui';
export default {
  created(){
    Toast({
      message: '对不起,服务器错误',
      iconClass: 'icon icon-success'
  });
 }
}
</script>

<style lang="scss" scoped>

</style>
