<template>
  <div class="header_bar">
    <div class="header_min_bar_top">
    <ul class="right_entry">
        <li class="liDisplay"><a href="#">首页</a></li>
        <li class="liDisplay">番剧</li>
        <li class="liDisplay">直播</li>
    </ul>
    <div class="header_search">
      <form class="search_form"></form>
    </div>
    </div>
  </div>
  <div class="header_channel"></div>
  <div class="header_layout"></div>
</template>
<script>
</script>



<style>
.header_bar {
  background: blue;
  width: 1920px;
  height: 155px;
}
.header_channel {
  background: red;
  width: 1920px;
  height: 100px;
}
.header_layout {
  background:green;
  width: 1920px;
  height: auto;
}
.header_min_bar_top{
    background: rgb(138, 234, 101);
  width: 1920px;
  height: 70px;
  display: flex;
}
.right_entry{
    background: rgb(202, 222, 194);
  width: 487px;
  height: 70px;
  margin-left:30px;
  margin-top: 0;
  margin-bottom: 0;
  padding: 0;
  display: flex;
 float: left;
}
.liDisplay{
  display: inline;
  align-self: center;
  margin: 20px;

}
.header_search{
  background: rgb(95, 82, 214);
  width: 487px;
  height: 70px;
  display: flex;
  justify-content: center; 
  align-items: center;  
}
.search_form{
    width: 250px;
    height: 40px;
    border-radius: 8xp;
    background: red;
}
</style>