<template>
  <div class="box1">
    <div class="input">
      <div class="input-left">
        <span class="iconfont">&#xe67f;</span>
      </div>
      <input class="input-box" type="text" placeholder="邮箱/手机号" />
    </div>
    <div class="interval"></div>
    <div class="input">
      <div class="input-left">
        <span class="iconfont">&#xe63e;</span>
      </div>
      <input class="input-box" type="text" placeholder="请输入密码" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'LoginInput'
}
</script>

<style lang="stylus" scoped>
  .box1
    border-top: .02rem solid #cecece
    border-bottom: .02rem solid #cecece
    background: #fff
    .input
      display: flex
      line-height: .76rem
      height: .76rem
      margin-left: .5rem
      margin-right: .5rem
      .input-left
        height: .56rem
        width: .38rem
        float: left
        .iconfont
          font-size: .4rem
      .input-box
        flex: 1
        height: .76rem
        line-height: .64rem
        /* margin-top: .1rem
        margin-left: .2rem */
        margin-right: .4rem
        border-radius: .1rem
        text-indent: .4rem
    .interval
      margin-left: .5rem
      margin-right: .5rem
      border-bottom: .02rem solid #cecece
</style>
