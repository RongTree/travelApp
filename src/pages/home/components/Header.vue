<template>
    <div class="header">
        <div class="header_left">
          <span class="iconfont qrcode_icon">&#xe618;</span>
        </div>
        <div class="header_input">
          <span class="iconfont search_icon">&#xe6c7;</span>
          <span class="input_tips">11.11酒店5折起</span>
          <span class="iconfont maikefeng_icon">&#xe600;</span>
        </div>
        <div class="header_right">
          <span class="iconfont message_icon">&#xe6a8;</span>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
  .header{
    display:flex;
    line-height:45px;
    background-color:rgb(0,0,0);
    color:#fff;
  }
  .header_left{
    width:45px;
    float:left;
    text-align:center;
  }
  .qrcode_icon{
    font-size:25px;
  }
  .header_input{
    flex:1;
    position:relative;
    background-color:rgb(230,230,230);
    border-radius:10px;
    margin:10px;
    color:rgb(106,115,125);
  }
  .input_tips{
    position:absolute;
    left:25px;
    top:-8px;
  }
  .search_icon{
    font-size:12px;
    position:absolute;
    top:-8px;
    left:8px;
  }
  .maikefeng_icon{
    position:absolute;
    top:-8px;
    right:10px;
  }
  .header_right{
    min-width:45px;
    float:right;
    text-align:center;
  }
  .message_icon{
    font-size:25px;
  }

</style>
