<template>
  <div class="wrapper">
    <div class="search">
  
      <header class="mw-header">
        <a  class="header-title-icon"></a>
        <div  class="mw-header_app">App查看</div>
        <div  class="title-search">
          <a  href="#" class="search-icon"></a>
        </div>
      </header>
  
    </div>
  </div>
</template>


<style lang="stylus" scoped>
.wrapper
  .search{
    height 1.28rem;
    width 100%;
    margin 0 auto;
    display flex;
    align-items center;
    justify-content center;
    background-color white;
  }
header.mw-header{
    height: 2.60667rem;
    background-color: #fff;
    width: 100%;
    box-sizing: border-box;
    padding: 0 1.26667rem 0 .8rem;
    display: flex;
    align-items: center;
}
header .header-title-icon {
    display: block;
    height: 100%;
    width: 6rem;
    background: url(https://edu-image.nosdn.127.net/54008497-10c4-4388-a34a-9a6f0f7fcdae.png?imageView&quality=100) 50% no-repeat;
    margin-right: .41333rem;
    margin-left: -1rem;
    background-size: contain;
}
header .mw-header_app{
    height: 0.45rem;
    width: 2.2rem;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
    color: #2cc17b;
    line-height: 0.45rem;
    text-align: center;
    border-radius: 0.53333rem;
    font-size: 12px;
    border: 1px solid #2cc17b;
    vertical-align: bottom;
    margin-left: -2.5rem;
}
header .title-search{
    -ms-flex-positive: 1;
    flex-grow: 1;
    display: -ms-flexbox;
    display: flex;
    -ms-flex-pack: end;
    justify-content: flex-end;
    -ms-flex-line-pack: center;
    align-content: center;
}
header .title-search .search-icon {
    display: inline-block;
    width: 24px;
    height: 24px;
    background: url(../assets/ssuo.png) no-repeat -25px 0;
    background-size: 63px;
}

</style>
