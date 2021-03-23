<template>
<div class="wrapper">

     <div class="search">
        <!-- span是横着的，div是竖着的 -->
        <span class="iconfont">&#xe672;</span>
        <span class="search__text">Search Bar</span>
      </div>
      <div class="banner">
        <img
          class="banner__img"
          src="https://www.incimages.com/uploaded_files/image/970x450/getty_522735456_249841.jpg"
        />
      </div>
      <div class="icons">
        <div class="icons__item">
          <img
            class="icons__item__img"
            src="https://maxcdn.icons8.com/Share/icon/p1em/business/shop1600.png"
          />
          <p class="icons__item__desc">Store</p>
        </div>
        <div class="icons__item">
          <img
            class="icons__item__img"
            src="https://maxcdn.icons8.com/Share/icon/p1em/business/shop1600.png"
          />
          <p class="icons__item__desc">Store</p>
        </div>
        <div class="icons__item">
          <img
            class="icons__item__img"
            src="https://maxcdn.icons8.com/Share/icon/p1em/business/shop1600.png"
          />
          <p class="icons__item__desc">Store</p>
        </div>
         <div class="icons__item">
          <img
            class="icons__item__img"
            src="https://maxcdn.icons8.com/Share/icon/p1em/business/shop1600.png"
          />
          <p class="icons__item__desc">Store</p>
        </div>
        <div class="icons__item">
          <img
            class="icons__item__img"
            src="https://maxcdn.icons8.com/Share/icon/p1em/business/shop1600.png"
          />
          <p class="icons__item__desc">Store</p>
        </div>
        <div class="icons__item">
          <img
            class="icons__item__img"
            src="https://maxcdn.icons8.com/Share/icon/p1em/business/shop1600.png"
          />
          <p class="icons__item__desc">Store</p>
        </div>
        <div class="icons__item">
          <img
            class="icons__item__img"
            src="https://maxcdn.icons8.com/Share/icon/p1em/business/shop1600.png"
          />
          <p class="icons__item__desc">Store</p>
        </div>
        <div class="icons__item">
          <img
            class="icons__item__img"
            src="https://maxcdn.icons8.com/Share/icon/p1em/business/shop1600.png"
          />
          <p class="icons__item__desc">Store</p>
        </div>
        <div class="icons__item">
          <img
            class="icons__item__img"
            src="https://maxcdn.icons8.com/Share/icon/p1em/business/shop1600.png"
          />
          <p class="icons__item__desc">Store</p>
        </div>
        <div class="icons__item">
          <img
            class="icons__item__img"
            src="https://maxcdn.icons8.com/Share/icon/p1em/business/shop1600.png"
          />
          <p class="icons__item__desc">Store</p>
        </div>
    </div>
    <div class="gap"></div>
    <div class="nearby">
        <h3 class="nearby__title">Nearby Stores</h3>
        <div class="nearby__item">
          <img
            src="https://th.bing.com/th/id/R7ae60f179ba0466a8de5502d0b24f267?rik=sKe04U1WUsj%2f5A&pid=ImgRaw"
            class="nearby__item__img"
          >
          <div class="nearby__content">
            <div class="nearby__content__title">App Store</div>
            <div class="nearby__content__tags">
              <span class="nearby__content__tag">Computer</span>
              <span class="nearby__content__tag">Phone</span>
              <span class="nearby__content__tag">iPad</span>
            </div>
          </div>
        </div>
        <div class="nearby__item">
          <img
            src="https://th.bing.com/th/id/R7ae60f179ba0466a8de5502d0b24f267?rik=sKe04U1WUsj%2f5A&pid=ImgRaw"
            class="nearby__item__img"
          >
          <div class="nearby__content">
            <div class="nearby__content__title">App Store</div>
            <div class="nearby__content__tags">
              <span class="nearby__content__tag">Computer</span>
              <span class="nearby__content__tag">Phone</span>
              <span class="nearby__content__tag">iPad</span>
            </div>
          </div>
        </div>
        <div class="nearby__item">
          <img
            src="https://th.bing.com/th/id/R7ae60f179ba0466a8de5502d0b24f267?rik=sKe04U1WUsj%2f5A&pid=ImgRaw"
            class="nearby__item__img"
          >
          <div class="nearby__content">
            <div class="nearby__content__title">App Store</div>
            <div class="nearby__content__tags">
              <span class="nearby__content__tag">Computer</span>
              <span class="nearby__content__tag">Phone</span>
              <span class="nearby__content__tag">iPad</span>
            </div>
          </div>
        </div>
    </div>
  </div>

<!-- Css的编码便准BEM block__element--Modifier,表示element是block中的元素，用下划线连接，
Modifier相当于激活/修改，此时用--连接-->
  <div class="docker">
    <div class="docker__item docker__item--active"> <!-- 输入div.item*4点击回车，自然生成4个div标签 -->
        <div class="iconfont">&#xe821;</div>
      <div class="docker__title">Home</div>
    </div>
    <div class="docker__item">
      <div class="iconfont">&#xe6af;</div>
      <div class="docker__title">Shopping</div>
      </div>
    <div class="docker__item">
      <div class="iconfont">&#xe60e;</div>
      <div class="docker__title">Orders</div>
    </div>
    <div class="docker__item">
      <div class="iconfont">&#xe660;</div>
      <div class="docker__title">My</div>
    </div>
  </div>
</template>

<style lang="scss" scroped>

.wrapper {
  position: absolute;
  left: 0;
  top: 0;
  bottom: .5rem;
  right: 0;
  padding: 0 25px;  //上下0， 左右25px
}

.search {
  margin-top: 20px;
  margin-bottom: 12px;
  line-height: 32px;
  background: #F5F5F5;
  color: #B7B7B7;
  border-radius: .16rem;  //搜索框的边框弧度
  .iconfont {
    display: inline-block;  //一个方块
    padding: 0 .08rem 0 .16rem;
    font-size: 25px;
  }
  &__text {
    display: inline-block;
    font-size: 25px;
  }
}

.banner {
  height: 0;
  overflow: hidden;
  padding-bottom: 25.4%;   //图片大小1528*388，388/1528=25.4%，25.4%代表屏幕高度的25.4%
  &__img {
    width: 100%;
  }
}
.icons {
  display: flex;  //横向展示
  flex-wrap: wrap;  //表示对图表进行换行
  margin-top: 20px; //整个10个图表为一个整体，距离上面16px
   &__item {
    width: 20%;
    &__img {
      display:block; //元素会以区块的形式进行展示，就是图表被外部的虚线正方形包裹后进行CSS的定义
      width: 20px;
      height: 20px;
      margin: 0 auto;
    }
    &__desc {
      margin: .06rem 0 .16rem 0;
      text-align: center;
      $content-fontcolor: #333;
    }
  }
}
.gap {
  margin: 0 -20px; //表示将灰色的gap区域撑开，超过wrapper的包裹，向外延展18px
  height: 1px;
  $content-bgColor: #F1F1F1;
}
.nearby {
  &__title {
    margin: 16px 0 2px 0;
    font-size: 18px;
    font-weight: normal;
     $content-fontcolor: #333;
  }
  &__item {
    display: flex;  //横向摆放
    padding-top: 12px;  //item 是图片和右边的整个的部分距离上面12px
    &__img {
      margin-right: 16px;// 图片与右边文字间距16px
      width: 56px;
      height: 56px;
    }
  }
  &__content {
    flex: 1;   //横向摆放的第一个
    padding-bottom: 12px;
    border-bottom: 1px solid  #F1F1F1;  //页面上item中的那条线
    &__title {
      line-height: 22px;
      font-size: 16px;
       $content-bgColor: #F1F1F1;
    }
    &__tags {
      margin-top: 8px;
      line-height: 18px;
      font-size: 13px;
      $content-bgColor: #F1F1F1;
    }
    &__tag {
      margin-right: 16px;  //每个tag距离右边16px,相当于tags的间距是16px
    }
  }

}
.docker {
  display: flex;  //横排显示
  box-sizing: border-box;   //边框
  position: absolute;
  padding: 0 25px;  //整个底边部分左右18px,上下为0
  left: 0;
  bottom: 0;
  width: 100%;
  height: 60px;
  border-top: 1px solid #F1F1F1;  //底边边框的上边框为白色， 1px
  &__item {                //表示docker__item
    flex: 1;               //横向均分，等分
    text-align: center;
    .iconfont {
      margin: .07rem 0 .02rem 0;  //上 右 下 左
      font-size: 18px;
    }
    &--active {            //表示docker__item--active
      color: #1FA4FC;
    }
  }
  &__title {                     // 表示docker__title
    font-size: 25px;            //浏览器默认的最小字体为12px
    transform: scale(.5, .5);  //横向缩小50%，纵向缩小50%，相当于字体是10px
    transform-origin: center top;  //以中心和顶点缩小
  }
}
</style>
