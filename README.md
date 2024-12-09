# IT-VISION-SCHOOL-CLASS_2
## my site
### html
```html
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>shj Portfolio</title>
  <script src="https://code.jquery.com/jquery-1.12.4.min.js" integrity="sha256-ZosEbRLbNQzLpnKIkEdrPv7lOy9C27hHQ+Xp8a4MxAQ=" crossorigin="anonymous"></script>
  <script src="https://kit.fontawesome.com/e990e4521f.js" crossorigin="anonymous"></script>
  <link href="https://cdn.jsdelivr.net/npm/reset-css@5.0.2/reset.min.css" rel="stylesheet">
  <link rel="stylesheet" href="./css/style.css">
  <script defer src="./js/script.js"></script>
</head>
<body>
  <!-- header -->
  <header>
    <div class="container">
      <h1>
        <button data-animation-scroll="true" data-target="#main">SHJ</button>
      </h1>
      <nav>
        <ul>
          <li>
            <button data-animation-scroll="true" data-target="#about">
              About
            </button>
          </li>
          <li>
            <button data-animation-scroll="true" data-target="#strength">
              Strength
            </button>
          </li>
          <li>
            <button data-animation-scroll="true" data-target="#portfolio">
              Portfolio
            </button>
          </li>
          <li>
            <button data-animation-scroll="true" data-target="#contact">
              Contact
            </button>
          </li>
        </ul>
      </nav>
    </div>
  </header>
  <!-- end header -->
  <!-- main -->
  <main id="main">
    <div class="container">
      <h4>Welcome to the SHJ site</h4>
      <h2 class="active">I`M A <span></span></h2>
      <p>SHJ의 포트폴리오 사이트에 오신 것을 환영합니다. <br>아래에 더 많은 정보가 있습니다.</p>
      <button class="icon"><i class="fa-solid fa-plane-up"></i></button>
    </div>
  </main>
  <!-- end main -->

  <!-- about me -->
  <section id="about" class="about">
    <div class="container">
      <div class="title">
        <h4>Who Am I</h4>
        <h2>Let me introduce myself</h2>
      </div>
      <div class="about_me">
        <div class="left">
          <img src="./images/about_me.jpg" alt="내 사진">
        </div>
        <div class="right">
          <h3>안녕하세요. <strong>저는 이비전입니다.</strong></h3>
          <p>현재 서울에 거주하며 학교를 다니고 있습니다. </p>
          
          <p>저는 긍정적이고 성실한 성격을 지녀 주변 사람들과 좋은 관계를 유지하려고 노력합니다. 여가 시간에는 게임을 즐기며,<br> 이를 통해 스트레스를 해소하고 창의력을 키웁니다.</p>

          <p> 지금은 인서울 대학을 위해 꾸준히 노력하고 있으며,<br> 앞으로 3d 게임 분야에서 전문가로 성장하고 싶습니다.</p>
          <p> 제 강점을 살려 계속해서 발전해 나가고 싶습니다. 감사합니다.</p>

          <div class="social_icon">
            <a href="#">
              <i class="fa-brands fa-facebook"></i>
            </a>
            <a href="#">
              <i class="fa-brands fa-instagram"></i>
            </a>
            <a href="#">
              <i class="fa fa-twitter" aria-hidden="true"></i>
            </a>
            <a href="#">
              <i class="fa-brands fa-youtube"></i>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- end about me -->

<!-- strength -->
<section id="strength" class="strength">
  <div class="container">
    <div class="title">
      <h4>strength</h4>
      <h2>My three strengths</h2>
    </div>
    <div class="strength_wrap">                
      <div class="strength_inner">
        <div class="icon">
          <i class="fa-solid fa-face-smile"></i>
        </div>
        <div class="content">
          <h3>성실함</h3>
          <p>어떤 일이나 책임을 끝까지 완수하는 태도를 가지고 있습니다. 주어진 과제를 성실히 이행하여 신뢰를 쌓는 사람입니다. 맡은 일을 소중히 여겨 지속적으로 노력하는 삶을 살아가고 있습니다.</p>
        </div>
      </div>        
      <div class="strength_inner">
        <div class="icon">
          <i class="fa-solid fa-wand-magic-sparkles"></i>     
        </div>
        <div class="content">
          <h3>꼼꼼함</h3>
          <p>작은 부분까지 세심하게 신경쓰고 주의를 기울여 일을 처리하는 성향을 가지고 있습니다. 실수나 놓치는 부분이 없도록 철저히 검토하고, 일을 체계적으로 처리하려고 노력하고 있습니다.</p>
        </div>
      </div>
      <div class="strength_inner">
        <div class="icon">
          <i class="fa-solid fa-star"></i>
        </div>
        <div class="content">
          <h3>내적인 힘</h3>
          <p>외부 환경이나 어려운 상황에서 흔들리지 않고 스스로를  지탱하며 극복할 수 있는 마음의 강인함을 가지고 있습니다. 저의 가치를 믿으며 끈기있게 목표를 추구하고 있습니다.
          </p>
        </div>
      </div>
    </div>
  </div>  
</section>
<!-- end strength -->
  
<!-- back_bg -->
<div class="back_bg"></div>
<!-- end back_bg -->

<!-- portfolio -->
<section id="portfolio" class="portfolio">
  <div class="container">
    <div class="title">
      <h4>My portfolio</h4>
      <h2>PortFolio</h2>
    </div>
    <div class="portfolio_me">
      <div class="portfolio_inner">
        <img src="./images/portfolio_1.jpg" alt="포트폴리오1">
        <strong>BRANDING</strong>
        <h3>Package Design</h3>
      </div>
      <div class="portfolio_inner">
        <img src="./images/portfolio_2.jpg" alt="포트폴리오2">
        <strong>SPACE</strong>
        <h3>Stage Design</h3>
      </div>
      <div class="portfolio_inner">
        <img src="./images/portfolio_3.jpg" alt="포트폴리오3">
        <strong>MARKETING</strong>
        <h3>Character Design </h3>
      </div>
      <div class="portfolio_inner">
        <img src="./images/portfolio_4.jpg" alt="포트폴리오4">
        <strong>3D</strong>
        <h3>Prop Design</h3>
      </div>
      <div class="portfolio_inner">
        <img src="./images/portfolio_5.jpg" alt="포트폴리오5">
        <strong>MARKETING</strong>
        <h3>Space Production</h3>
      </div>
      <div class="portfolio_inner">
        <img src="./images/portfolio_6.jpg" alt="포트폴리오6">
        <strong>BROADCASTING</strong>
        <h3>Stage Production</h3>
      </div>
    </div>
  </div>
</section>
<!-- end portfolio -->

<!-- contact -->
<section id="contact" class="contact">
  <div class="container">
    <div class="title">
      <h4>CONTACT</h4>
      <h2>Contact With Me</h2>
    </div>
    <div class="contact_me">
      <div class="left">
        <div class="box">
          <div class="info_text">
            <h3>PHONE</h3><br>
            <p>010-5486-1004</p>
          </div>
        </div>
        <div class="box">
          <div class="info_text">
            <h3>EMAIL</h3><br>
            <p>1004@naver.com</p>
          </div>
        </div>
        <div class="box">
          <div class="info_text">
            <h3>ADDRESS</h3><br>
            <p>서울시 노봉구 순환로28 풍산아파트 209호</p>
          </div>
        </div>
      </div>
      <div class="right">
        <form action="#">
          <div class="form_group">
            <label for="name">name</label>
            <input type="text" id="name">
          </div>
          <div class="form_group">
            <label for="email">email</label>
            <input type="text" id="email">
          </div>
          <div class="form_group">
            <label for="msg">message</label>
            <textarea id="msg"></textarea>
          </div>
          <button>SEND</button>
        </form>
      </div>
    </div>
  </div>
</section>
<!-- end contact -->
```
### css
```css
/* common */
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@100..900&family=Sunflower:wght@300;500;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Black+Han+Sans&family=Inria+Serif:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Nanum+Brush+Script&family=Noto+Sans+KR:wght@100..900&display=swap');
*{
  margin:0;
  padding:0;
  box-sizing: border-box;
}
a, a:link, a:visited{
  color:inherit;
  text-decoration:none;
}
li{
  list-style:none;
}
.container{
  width:1100px;
  margin:0 auto;
}
section{
  font-family: "Noto Sans KR", sans-serif;
  font-optical-sizing: auto;
  font-weight: 700;
  font-style: normal;
  padding:5rem 0;
}
section:nth-child(2n){
  background-color:#f8f8f8;
}
section .title{
  margin-bottom:3rem;
}
section .title h4{
  font-size: 1.35rem;
  padding-bottom: 10px;
  color:#48ed8f;
  position:relative;
}
section .title h2{
  font-size:3.5rem; 
}
section .title p{
  font-size:1.15rem;
}

/* header main */
/* header */
header{
  position:fixed;
  color:white;
  top:0;
  z-index:1;
  width:100%;
  padding:1rem;
}
header .container{
  display:flex;
  justify-content:space-between;
  align-items:center;
  width:100%;
}
header nav ul{
  display:flex;
}
header nav ul li{
  padding:10px;
}
header button{
  background: transparent;
  border:0;
  cursor: pointer;
  color:white; 
}
header h1 button{
  font-size: 2rem;
  font-weight: bold;
}
header nav ul li button{
  font-size: 1.3rem;
}
/* End header */

/* main*/
main{
  width:100%;
  height:100vh;
  color:white;
  background:linear-gradient(rgba(0,0,0,0.8), rgba(0,0,0,0.8)), url('../images/main_bg_1.jpg') center center;
  background-size:cover;
  display:flex;
  justify-content:center;
  align-items:center;
  text-align:center;
}
main h4{
  font-size:2rem;
}
main h2{
  font-size:3rem;
  margin:2rem 0;
  letter-spacing:3px;
  font-family: "Black Han Sans", sans-serif;
  font-weight: 400;
  font-style: normal;
}
main p{
  max-width:500px;
  margin:0 auto;
  font-size:1.25rem;
  line-height: 30px;
  font-weight: 400; 
}

main button.icon{
  background-color:transparent;
  border:none;
  color:white;
  font-size:2rem;
  position:absolute;
  bottom:1rem;
  left:50%;
  transform:translateX(-50%);
  animation:upDown 1s ease-in-out infinite;
  cursor:pointer;
}
@keyframes upDown{
  0%{
    bottom:1rem;
  }
  50%{
    bottom:1.5rem;
  }
  100%{
    bottom:1rem;
  }
}
main h2 span::after{
  content:"";
  height:40px;
  width:3px;
  background-color:#fff;
  display:inline-block;
  animation: blink .7s ease-in-out infinite;
}
@keyframes blink {
  0%{
    opacity: 1;
  }
  100%{
    opacity: 0;
  }
}
/* End main */

/* about_me */

section .about_me::after{
  content:"";
  clear:both;
  display:block;
}
section .about_me .left{
  width:50%;
  float:left;
}
section .about_me .left img{
  max-width:100%;
}
section .about_me .right{
  width:50%;
  float:left;
  padding:0 2rem;
}
section .about_me .right h3{
  font-size:2.25rem;
  margin-bottom:1rem;
}
section .about_me .right h3 strong{
  color:#48ed8f;
}
section .about_me .right p{
  font-size:1.15rem;
  margin:1rem 0;
  font-weight: 400;
}
section .about_me .right .social_icon a{
  font-size:2.5rem;
  margin-right:0.2rem;
}
section .about_me .right .social_icon a:hover{
  color:#48ed8f;
}
/* end about_me */

/* strength */
section.strength {
  background-color:#f1f1f1;
}
section .strength_wrap::after{
  content:"";
  display:block;
  clear:both;
}
section .strength_wrap .strength_inner{
  background-color:#ffffff;
  width: 30%;
  padding:2rem; 
  float:left;
  margin-right:5%;
  cursor:pointer;
}
section .strength_wrap .strength_inner:last-child{
  margin-right:0;
}
section .strength_wrap .strength_inner .icon i{
  font-size:2.5rem;
  color:#48ed8f;
}
section .strength_wrap .strength_inner .content h3{
  font-size:2rem;
  margin:1rem 0;
}
section .strength_wrap .strength_inner .content p{
  font-size:1.15rem;
  font-weight: 400;
}
section .strength_wrap .strength_inner:hover{
  background-color:#4dd588;
  color:white;
}
section .strength_wrap .strength_inner:hover i{
  color:white;
}

/* back_bg */
.back_bg{
  background:url('../images/back_bg.jpg') center center;
  background-size:cover;
  background-attachment:fixed;
  height:650px;
}

/* portfolio */
section.portfolio::after{
  content:"";
  display:block;
  clear:both;
}
section.portfolio .portfolio_inner{
  width:30%;
  margin-right:5%;
  padding:1rem 1rem 1.5rem 1rem;
  float:left;
  background-color:#f8f8f8;
  border:1px solid #ccc;
  margin-bottom:3rem;
}
section.portfolio .portfolio_inner:nth-child(3n){
   margin-right:0;
}
section.portfolio .portfolio_inner img{
  width:100%;
  display:block;
}
section.portfolio .portfolio_inner strong{
  color:#48ed8f;
  margin:0.5rem 0;
  display:block;
}
section.portfolio .portfolio_inner h3{
  font-size:1.75rem;
}


/* contact */
section.contact .contact_me::after{
  content:"";
  display:block;
  clear:both;
}
section.contact .contact_me .left{
  width:30%;
  float:left;
}
section.contact .contact_me .right{
  float:left;
  width:65%;
  margin-left:5%;
}
section.contact .contact_me .left .box{
  border:1px solid #ccc;
  padding:18px;
  display:flex;
  align-items:center;
  margin-bottom:15px;
}
section.contact .contact_me .left .box .info_text p{
  font-weight: 400;
}
section.contact .contact_me .right{ 
  float:left;
  width:65%;
  margin-left:5%;
  margin-bottom:20px;
  border:1px solid #ccc;
  padding:18px;
}

section.contact .contact_me .right .form_group{
  margin-bottom:1.25rem;
}

section.contact .contact_me .right .form_group label{
  display:block;
  margin-bottom:0.85rem;
}

section.contact .contact_me .right .form_group input{
  padding:0.6rem;
  width:100%;
  outline:none;
  border:1px solid #ccc;
}

section.contact .contact_me .right .form_group input:focus{
  border:1px solid #12ff91;
}

section.contact .contact_me .right .form_group textarea{
  height:300px;
  width:100%;
  resize:none;
  border:1px solid #ccc;
}

section.contact .contact_me .right .form_group textarea:focus{
  outline:none;
  border:1px solid #12ff91;
}

section.contact .contact_me .right button{
  width:100%;
  padding:1rem;
  background-color:#48ed8f;
  border:none;
  color:rgb(19, 19, 19);
  font-weight: bold;
  font-size: 20px;
}
/* end contact */

/* media */
@media screen and (max-width: 1100px){
  main .container{
    width: 992px;
  }
  section .container{
    width:600px;
  }
  section .about_me .left{
    width:100%;
    margin-bottom: 1.5rem;
  }
  section  .about_me .right{
    width:100%;
    padding:0;
  }
  section .strength_wrap .strength_inner{
    width:48%;
    margin-bottom: 1.5rem;
    margin-right: 0;
  }
  section .strength_wrap .strength_inner:nth-child(2n+1){
    margin-right:4%; 
  }
  section .portfolio_me .portfolio_inner{
    width:48%;
    margin-right: 0;
  }
  section .portfolio_me .portfolio_inner:nth-child(2n+1){
    margin-right:4%;
  }
  section.contact .contact_me .left{
    width:100%; 
  }
  section.contact .contact_me .right{
    width:100%;
    margin-left: 0; 
    
  }
}

@media (max-width: 992px){
  html{
    font-size: 14px;
  }
  main .container{
    width: 768px; 
  }
  section .portfolio_me .portfolio_inner{
    width:100%; 
  } 
}

@media (max-width: 768px){
  html{
    font-size: 13px;
  }
  main .container{
    width: 576px; 
  }
  section .container{
    width:400px; 
  }
  section .strength_wrap .strength_inner{
    width:100%; 
    margin-right: 0; 
  }
}

@media (max-width: 576px){
  
  html{
    font-size: 12px;
  }
  main .container{
    width: 400px; 
  }
  section .container{
    width:360px; 
  }
}

@media (max-width: 400px){
  
  html{
    font-size: 11px;
  }
  main .container{
    width: 320px;
  }
  main h4{
    font-size: 1.5rem;
  }
  section .container{
    width: 320px;
  }
  section .title h2{
    font-size: 3rem; 
  }
}

/* header active */
header.active{
  background-color:rgba(0,0,0);
  animation:fadeIn 0.5s ease-in-out;
}
@keyframes fadeIn{
  0%{
    opacity:0;
  }
  100%{
    opacity:1;
  }
}
```
### js
```js
// 글자 생성
(function(){
  const spanEl = document.querySelector("main h2 span");
  const txtArr = ['Front-End Developer', 'Web UI Designer', 'UX Designer', 'Web Publisher', '3d Designer', 'Back-End Developer'];
  let index = 0;
  let currentTxt = txtArr[index].split("");
  function writeTxt(){
    spanEl.textContent  += currentTxt.shift(); 
    if(currentTxt.length !== 0){ 
      setTimeout(writeTxt, Math.floor(Math.random() * 100));
    }else{
      currentTxt = spanEl.textContent.split("");
      setTimeout(deleteTxt, 3000);
    }
  }
  function deleteTxt(){
    currentTxt.pop();
    spanEl.textContent = currentTxt.join("");
    if(currentTxt.length !== 0){
      setTimeout(deleteTxt, Math.floor(Math.random() * 100))
    }else{
      index = (index + 1) % txtArr.length;
      currentTxt = txtArr[index].split("");
      writeTxt();
    }
  }
  writeTxt();
})();

/*  header 태그에 active 클래스 추가 및 삭제 */
const headerEl = document.querySelector("header");
window.addEventListener('scroll', function(){
  requestAnimationFrame(scrollCheck);
});
function scrollCheck(){
  let browerScrollY = window.scrollY ? window.scrollY : window.pageYOffset;
  if(browerScrollY > 0){
    headerEl.classList.add("active");
  }else{
    headerEl.classList.remove("active");
  }
}

/* 애니메이션 스크롤 이동 */
const animationMove = function(selector){
const targetEl = document.querySelector(selector);
const browserScrollY = window.pageYOffset;
const targetScorllY = targetEl.getBoundingClientRect().top + browserScrollY;
 window.scrollTo({ top: targetScorllY, behavior: 'smooth' });
};
// 스크롤 이벤트 연결하기
const scollMoveEl = document.querySelectorAll("[data-animation-scroll='true']"); 
for(let i = 0; i < scollMoveEl.length; i++){
  scollMoveEl[i].addEventListener('click', function(e){
    const target = this.dataset.target;
    animationMove(target);
  });
}



```

## 폰트어썸 스크립트
### html
```html
<script src="https://kit.fontawesome.com/e990e4521f.js" crossorigin="anonymous"></script>
```

## 지난시간 about_me
### html
```html
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>about_me</title>
  <link rel="stylesheet" href="./css/common.css">
  <link rel="stylesheet" href="./css/about_me.css">
</head>
<body>
  <section id="about" class="about">
    <div class="container">
      <div class="title">
        <h4>Who Am I</h4>
        <h2>Let me introduce myself</h2>
      </div>
      <div class="about_me">
        <div class="left">
          <img src="./image/me.jpg" alt="내 사진">
        </div>
        <div class="right">
          안녕하세요. 저는 ooo입니다.
          현재 서울에 거주하며 학교를 다니고 있습니다.
          저는 긍정적이고 성실한 성격을 지녀 주변 사람들과 좋은 관계를 유지하고 있습니다.
          여가 시간에는 게임을 즐기며,지금은 인서울 대학을 위해 꾸준히 노력하고 있습니다.
          앞으로 3d 게임 분야에서 전문가로 성장하고 싶습니다.제 강점을 살려 계속해서 발전해 나가려고 노력하고 있습니다. 감사합니다.
        </div>
      </div>
    </div>
  </section>
</body>
</html>
```

## 로그인 페이지 만들기 
### html
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
### css
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
   width: 100%;
  padding: 12px 15px;
  border: 1px solid #ddd;
  border-radius: 4px;
  font-size: 16px;
  background-color: #fafafa;
}
.login_button {
  width: 100%;
  padding: 14px 0;
  background-color: #03C75A;
  color: white;
  border: none;
  border-radius: 4px;
  font-size: 18px;
  cursor: pointer;
  margin-top: 20px;
}

.login_button:hover {
  background-color: #02a04d;
}
.extra_options {
  margin-top: 20px;
  font-size: 14px;
  color: #666;
}

.extra_options a {
  color: #666;
  text-decoration: none;
  margin: 0 5px;
}

.extra_options a:hover {
  text-decoration: underline;
}
```
