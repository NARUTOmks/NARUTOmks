<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<title>全屏背景图片</title>
<style>
  /* 设置整个页面的背景图片 */
  body {
    margin: 0; /* 移除默认的边距 */
    padding: 0; /* 移除默认的内边距 */
    background-image: url('主页.png'); /* 替换为您的背景图片路径 */
    background-size: cover; /* 背景图片覆盖整个页面 */
    background-attachment: fixed; /* 背景图片固定，不会随页面滚动 */
    background-position: center center; /* 背景图片居中显示 */
    height: 100vh; /* 将body高度设置为视口高度的100% */
  }

  /* 创建一个图片按钮 */
  .button-image {
    position: fixed; /* 将按钮固定在页面某个位置 */
    bottom: 100px; /* 距离页面底部10像素 */
    right:300px; /* 距离页面右边10像素 */
    cursor: pointer; /* 鼠标悬停时显示手型光标 */
  }

  /* 按钮图片 */
  .button-image img {
    width: 400px; /* 按钮图片宽度 */
    height: 200px; /* 按钮图片高度 */
  }
</style>
<script>
  // JavaScript 函数，用于处理按钮点击事件
  function handleClick() {
    // 打开新的 HTML 文件
    window.open('hk.html');
  }
</script>
</head>
<body>

<!-- 创建一个图片按钮 -->
<div class="button-image" id="button" onclick="handleClick()">
  <img src="按钮.png" alt="按钮图片">
</div>

</body>
</html>![主页](https://github.com/NARUTOmks/NARUTOmks/assets/163805563/f67b4a12-d24b-47db-a7a3-c20badc14fa2)
![按钮](https://github.com/NARUTOmks/NARUTOmks/assets/163805563/3b25d076-6031-44d1-9099-1fc3a9b1d6c6)
