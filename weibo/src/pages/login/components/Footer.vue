<template>
  <div class="footer">
    <a class="register" href="www.baidu.com">注册账号</a>
    <a class="forget" href="www.baidu.com">忘记密码</a>
  </div>
</template>

<script>
export default {
  name: 'LoginFooter'
}
</script>

<style lang="stylus" scoped>
  .footer
    margin-top: 0.52rem
    text-align:center
    .register
      font-size: .3rem
      color: #416fa1
      margin-right: .3rem
      padding-right: .3rem
      border-right: 0.02rem solid #cecece
    .forget
      font-size: .3rem
      color: #416fa1
</style>
