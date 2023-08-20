<!DOCTYPE html>
<html>
<head>
<style>
  body {
    font-family: Times new roman, sans-serif;
    margin: 0;
    padding: 0;
  }
  
  .container {
    width: 80%;
    margin: 0 auto;
    background-color: #f2f2f2;
    padding: 20px;
    box-sizing: border-box;
  }
  
  .title {
    background-color: #AA336A;
    text-align:center;
    color: white;
    padding: 10px;
    border:2px solid blue;
  }
  
  .content {
    float: left;
    width: 70%;
    padding: 10px;
    font-family:verdana ;
    box-sizing: border-box;
  }
  
  .sidebar {
    float: right;
    width: 30%;
    padding:10px;
    font-family:verdana;
    box-sizing: border-box;
  }
  
  .clear {
    clear: both;
  }
</style>
</head>
<body>

<div class="container">
  <div class="title">Title Region</div>
  <div class="content">Main Content</div>
  <div class="sidebar">Sidebar Content</div>
  <div class="clear"></div>
</div>

</body>
</html>
