<template>
  <div class="logo">
    <img class="logo-img" src="https://passport.weibo.cn/images/weibo/signin/default-avatar_2x.png" />
  </div>
</template>

<script>
export default {
  name: 'LoginLogo'
}
</script>

<style lang="stylus" scoped>
  .logo
    margin-bottom:.6rem
    margin-top: 1.7rem
    .logo-img
      height: 1.41rem
      width: 1.41rem
      /* border: 1px dashed green */
      border: 0.02rem solid #cecece
      display: table-cell
      text-align: center
      margin: auto

</style>
