<template>
  <div>
    <div class="search">
      <div class="search-box">
        <input placeholder="搜索">
      </div>
    </div>
    <swiper class="banner" indicator-dots indicator-color="rgba(255, 255, 255, 0.6)" indicator-active-color="#fff">
      <swiper-item>
        <image src="/static/uploads/banner1.png" />
      </swiper-item>
      <swiper-item>
        <image src="/static/uploads/banner2.png" />
      </swiper-item>
      <swiper-item>
        <image src="/static/uploads/banner3.png" />
      </swiper-item>
    </swiper>
    <div class="navs">
      <navigator>
        <image src="/static/uploads/icon_index_nav_1@2x.png" />
      </navigator>
      <navigator>
        <image src="/static/uploads/icon_index_nav_2@2x.png" />
      </navigator>
      <navigator>
        <image src="/static/uploads/icon_index_nav_3@2x.png" />
      </navigator>
      <navigator>
        <image src="/static/uploads/icon_index_nav_4@2x.png" />
      </navigator>
    </div>
    <div class="floor">
      <div class="f-title">
        <image src="/static/uploads/pic_floor01_title.png" />
      </div>
      <div class="f-box">
        <div>
          <image src="/static/uploads/pic_floor01_1@2x.png" />
        </div>
        <div>
          <image src="/static/uploads/pic_floor01_2@2x.png" />
          <image src="/static/uploads/pic_floor01_3@2x.png" />
          
        </div>
        <div>
          <image src="/static/uploads/pic_floor01_4@2x.png" />
          <image src="/static/uploads/pic_floor01_5@2x.png" />
        </div>
      </div>
    </div>
    <div class="floor">
      <div class="f-title">
        <image src="/static/uploads/pic_floor02_title.png" />
      </div>
      <div class="f-box">
        <div>
          <image src="/static/uploads/pic_floor02_1@2x.png" />
        </div>
        <div>
          <image src="/static/uploads/pic_floor02_2@2x.png" />
          <image src="/static/uploads/pic_floor02_3@2x.png" />
          
        </div>
        <div>
          <image src="/static/uploads/pic_floor02_4@2x.png" />
          <image src="/static/uploads/pic_floor02_5@2x.png" />
        </div>
      </div>
    </div>
    <div class="floor">
      <div class="f-title">
        <image src="/static/uploads/pic_floor03_title.png" />
      </div>
      <div class="f-box">
        <div>
          <image src="/static/uploads/pic_floor03_1@2x.png" />
        </div>
        <div>
          <image src="/static/uploads/pic_floor03_2@2x.png" />
          <image src="/static/uploads/pic_floor03_3@2x.png" />
          
        </div>
        <div>
          <image src="/static/uploads/pic_floor03_4@2x.png" />
          <image src="/static/uploads/pic_floor03_5@2x.png" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.search-box {
  padding: 16rpx 30rpx;
  background-color: #ea4451;

}
.search-box input {
  background-color: #fff;
  text-align: center;
  font-size: 30rpx;
}
.banner {
  width: 750rpx;
  height: 320rpx;
}
.banner image {
  width: 750rpx;
  height: 320rpx;
}
.navs {
  display: flex;
  padding: 20rpx 0;
  justify-content: space-around;
}
.navs image {
  width: 128rpx;
  height: 140rpx;
}
.f-title image{
  width: 750rpx;
  height: 60rpx;
}
.f-box {
  overflow: hidden;
}
.f-box div{
  float: left;
}
.f-box div:nth-child(1) image{
  width: 223rpx;
  height: 386rpx;
  margin-right: 10rpx;
  margin-left: 20rpx;
}
.f-box div:nth-child(2) image,.f-box div:nth-child(3) image{
  width: 223rpx;
  height: 188rpx;
  margin-right: 10rpx;
}
</style>
