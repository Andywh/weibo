<template>
  <div>
    <ul>
      <li class="item border-bottom">
        <div class="header">
          <img class="item-img" src='https://tvax1.sinaimg.cn/crop.102.0.1865.1865.180/7fde8b93ly8fkf4lslnukj21kw1kwneg.jpg' />
          <div class="item-info">
            <p class="item-name">乡村教师代言人-马云</p>
            <p class="item-time">06-23 来自 微博 weibo.com</p>
          </div>
        </div>
        <div class="item-text">
          <p>去非洲看野生动物的时候，记得对这些巡护员敬礼致敬，带去问候[鲜花][鲜花]。过去，打死狮子大象犀牛的是英雄，而今天这些保护狮子大象犀牛的人才是真正的英雄！！</p>
        </div>
        <div class="item-interval"></div>
        <div class="item-footer">
          <div class="item-transmit">
              <div class="iconfont">&#xe790;</div>
              <p class="transmit">1314</p>
          </div>
          <div class="item-comment">
              <div class="iconfont">&#xe7d2;</div>
              <p class="comment">5924</p>

          </div>
          <div class="item-agree">
              <div class="iconfont">&#xe64a;</div>
              <p class="agree">1.4万</p>
          </div>
        </div>
      </li>
      <li class="item border-bottom">
        <div class="header">
          <img class="item-img" src='https://tva2.sinaimg.cn/crop.0.0.750.750.180/6ce2a3d1jw8f359ugioszj20ku0kudgh.jpg' />
          <div class="item-info">
            <p class="item-name">王思聪</p>
            <p class="item-time">05-12 来自 iPhone X</p>
          </div>
        </div>
        <div class="item-text">
          <p>韩国mnet估计后悔死了卖给tx这个101的版权...</p>
        </div>
        <div class="item-interval"></div>
        <div class="item-footer">
          <div class="item-transmit">
              <div class="iconfont">&#xe790;</div>
              <p class="transmit">3万</p>
          </div>
          <div class="item-comment">
              <div class="iconfont">&#xe7d2;</div>
              <p class="comment">12.4万</p>

          </div>
          <div class="item-agree">
              <div class="iconfont">&#xe64a;</div>
              <p class="agree">28.9万</p>
          </div>
        </div>
      </li>
      <li class="item border-bottom">
        <div class="header">
          <img class="item-img" src='https://tvax4.sinaimg.cn/crop.12.0.1218.1218.180/538efefbly8fj9msg96bmj20yi0xuacw.jpg' />
          <div class="item-info">
            <p class="item-name">左耳朵耗子</p>
            <p class="item-time">08-25 来自 iPhone客户端</p>
          </div>
        </div>
        <div class="item-text">
          <p>有人问我现在的年轻人是否更容易成功了，我说，当然喽。像我那个时代，成功要找人看个人字、手相、面相，风水，到寺庙里拜个佛、烧柱香、求个签、买个佛器，不但要花钱，还要改变自己干很多细枝末节的事情，还不一定能成功。现在的年轻人，只需要在网上转发个锦鲤就可以成功了……感觉有点身不逢时啊。 ​​​</p>
        </div>
        <div class="item-interval"></div>
        <div class="item-footer">
          <div class="item-transmit">
              <div class="iconfont">&#xe790;</div>
              <p class="transmit">63</p>
          </div>
          <div class="item-comment">
              <div class="iconfont">&#xe7d2;</div>
              <p class="comment">29</p>

          </div>
          <div class="item-agree">
              <div class="iconfont">&#xe64a;</div>
              <p class="agree">109</p>
          </div>
        </div>
      </li>

    </ul>
  </div>
</template>

<script>
export default {
  name: 'HomeTimeLine'
}
</script>

<style lang="stylus" scoped>
  .item
    overflow: hidden
    background: #fff
    border-bottom: 0.26rem solid #efefef
    .header
      display: flex
      .item-img
        height: .68rem
        width: .68rem
        margin-top: .3rem
        margin-left: .3rem
        border-radius: .4rem
      .item-info
        margin-top: .4rem
        margin-left: .2rem
        dispaly: flex
        flex: 1
        .item-name
          color: black
          font-size: .3rem
          margin-bottom: .1rem
          color: #ee4b06
        .item-time
          color: #818181
          font-size: .2rem
    .item-text
      font-size: .36rem
      margin-top: .3rem
      margin-left: .3rem
      margin-right: .3rem
      margin-bottom: .3rem
      line-height: .54rem
      dispaly: flex
    .item-interval
      border-bottom: .01rem solid #cecece
    .item-footer
      height: .72rem
      border-bottom: .01rem solid #cecece
      display: flex
      color: gray
      .item-transmit
        margin-left: .8rem
        margin-top: .2rem
        display: flex
        .iconfont
          font-size: .4rem
        .transmit
          margin-left:.1rem
          margin-top: .04rem
      .item-comment
        margin: auto
        margin-top: .2rem
        display: flex
        .iconfont
          font-size: .4rem
        .comment
          margin-left:.1rem
          margin-top: .04rem
      .item-agree
        margin-right: .8rem
        margin-top: .16rem
        display: flex
        .iconfont
          font-size: .4rem
        .agree
          margin-left:.1rem
          margin-top: .08rem
</style>
