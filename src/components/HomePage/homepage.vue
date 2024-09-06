<template>
  <div class="header_bar">
    <div class="header_min_bar_top">
    <ul class="right_entry">
        <li class="liDisplay"><a href="#">首页</a></li>
        <li class="liDisplay">番剧</li>
        <li class="liDisplay">直播</li>
    </ul>
    <div class="header_search">
      <form class="search_form">
        <div class="search_content">
          <input type="text" class="search_input" ref="search_ex">
        </div>
        <div class="search_btn">
          
        </div>
      </form>
    </div>
    </div>
  </div>
  <div class="header_channel"></div>
  <div class="header_layout"></div>
</template>
<script>

</script>

<style>
/*#region header*/
/*#region left_entry*/
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
/*#endregion left_entry*/
/*#region search*/
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
    display: flex;
    align-items: center;
    border: 1px solid #ccc;
    border-radius: 10px;
    background-color: #fff;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}
.search_content{
  width: 200px;
  height: 32px;
  display: flex;
  align-items: center;
  background-color: red;
  border-radius: 10px;
  margin-left: 5px;
  margin-right: 10px;
}
.search_input{
  width: 168px;
  height: 20px;
  border: 0;
  margin:8px
}
.search_btn{
  width: 32px;
  height: 32px;
  background: green;
  border-radius: 10px;
}
/*#endregion*/
/*#endregion*/
</style>
<style>

</style>
