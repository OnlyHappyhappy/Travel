<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont">&#xe624;</div>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe632;</span>
      请输入城市/景点</div>
    <div class="header-right">
        <span class="iconfont">&#xe600;</span>
      城市</div>
  </div>
</template>

<script>
export default {
  name: "HomeHeader"
};
</script>

<style lang="scss" scoped>
  @import '../../../assets/styles/varibles.scss';
    .header {
       line-height:.86rem;
        display:flex;
        background-color:$baseColor;
        color: #ffff;
        .header-left{
            width:.64rem;
            float:left;
            
        }
        .header-input{
            flex:1;
            background:#fff;
            margin-top: .12rem;
            height: .64rem;
            line-height: .64rem;
            margin-left: .2rem;
            color: #ccc;
            border-radius: .1rem;
            padding-left: .2rem;
        }
        .header-right{
            width:1.24rem;
            float:right;
            text-align:center;
        }
    }

    

</style>


