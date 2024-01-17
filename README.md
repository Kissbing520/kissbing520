<!DOCTYPE html>
<html lang="zh">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>资讯网站</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
  }
  .header {
    background-color: #fff;
    padding: 10px;
    text-align: center;
    border-bottom: 1px solid #ddd;
  }
  .search-bar {
    display: flex;
    justify-content: space-between;
    margin: 10px;
  }
  .search-bar input {
    width: 90%;
    padding: 10px;
    font-size: 16px;
  }
  .news-item {
    border-bottom: 1px solid #ddd;
    padding: 10px;
    display: flex;
    flex-direction: column;
  }
  .news-title {
    font-size: 18px;
    color: #333;
  }
  .news-content {
    font-size: 14px;
    color: #666;
  }
</style>
</head>
<body>
<div class="header">
  <h1>ODAILY</h1>
</div>
<div class="search-bar">
  <input type="text" placeholder="搜索">
  <button>搜索</button>
</div>
<div class="news-item">
  <div class="news-title">标题1</div>
  <div class="news-content">内容摘要1</div>
</div>
<div class="news-item">
  <div class="news-title">标题2</div>
  <div class="news-content">内容摘要2</div>
</div>
<!-- 更多新闻项目 -->
</body>
</html>
