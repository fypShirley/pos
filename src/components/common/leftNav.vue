<template>
  <div class="left-nav">
     <ul>
       <li>
         <i class="icon iconfont icon-goumai"></i>
         <div>收银</div>
       </li>
       <li>
         <i class="icon iconfont icon-dianpu"></i>
         <div>店铺</div>
       </li>
       <li>
         <i class="icon iconfont icon-hanbao"></i>
         <div>商品</div>
       </li>
       <li>
         <i class="icon iconfont icon-zuanshi"></i>
         <div>会员</div>
       </li>
       <li>
         <i class="icon iconfont icon-31qiandao"></i>
         <div>统计</div>
       </li>
       <li>
         <i class="icon iconfont icon-gongnengjianyi"></i>
         <div>设置</div>
       </li>
     </ul>
  </div>
</template>

<script>
export default {
  name: 'pos',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this  component only -->
<style>
  .left-nav{
    color:#fff;
    font-size: 12px;
    height: 100%;
    background: #1D8ce0;
    float: left;
    width: 5%;
  }
  .iconfont{
    font-size: 24px;
/*     color: #000; */
  }
  .left-nav ul{
    padding: 0;
    margin: 0;
  }
  .left-nav li{
    list-style: none;
    text-align: center;
    border-bottom: 1px solid #20a0ff;
    padding: 10px;
  }
</style>
