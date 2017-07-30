<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>form表单</title>
</head>
<body>
  <form action="/login" method="GET">
    <div class="username">
      <label for="username">用户名：</label>
      <input id="username" type="text" placeholder="username">
    </div>
    <div class="password">
      <label for="password">密码：</label>
      <input id="password" type="password" placeholder="password">
    </div>
    <div class="submit">
      <input type="submit" value="提交">
    </div>
  </form>  
</body>
</html>