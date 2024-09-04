# IT-VISION-SCHOOL-CLASS_2
#### 로그인 페이지 만들기 
## html
```html
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login</title>
  <link rel="stylesheet" href="./css/main.css">
</head>
<body>
  <div class="login_container">
    <h2 class="login_title">LOGIN</h2>
      <form action="#" method="post">
          <div class="input_group">
              <input type="text" id="username" name="username" placeholder="아이디" required>
          </div>
          <div class="input_group">
              <input type="password" id="password" name="password" placeholder="비밀번호" required>
          </div>
          <button type="submit" class="login_button">로그인</button>
          <div class="extra_options">
              <a href="#">아이디 찾기</a>
              <span>|</span>
              <a href="#">비밀번호 찾기</a>
              <span>|</span>
              <a href="#">회원가입</a>
          </div>
      </form>
</div>
</body>
</html>
```
## css
```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif;
  background-color: #f4f4f4;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh; 
  padding: 10px;
}

.login_container {
  background-color: #fff;
  padding: 40px 20px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  width: 100%;
  max-width: 400px;
  text-align: center;
}

.login_title {
  font-size: 36px;
  color: #03C75A;
  margin-bottom: 30px;
  font-weight: bold;
}

.input_group {
  margin-bottom: 15px;
}

.input_group input {
  수업시간에 다시 넣기
}
```
