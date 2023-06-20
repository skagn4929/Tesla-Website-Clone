# Tesla-Website-Clone
**HTML과 CSS를 사용하여 테슬라 웹사이트 클론을 만들어 보았습니다.**
- https://skagn4929.github.io/Tesla-Website-Clone/

![테슬라 클론 완성본](https://github.com/skagn4929/Tesla-Website-Clone/assets/134206709/11bedbb1-5b46-4a0b-9b90-5e394b9fbebb)

---

## 1. 프로젝트의 동기   
**클론 코딩을 통한 HTML 과 CSS 언어의 학습**

## 2. 프로젝트 주요 내용   
**1. 헤더섹션에 테슬라 로고와 자동차 리스트 그 외 메뉴 버튼을 만들었습니다.**
- HTML
```html
<header>
  <nav>
    <img src="logo.png" class="logo" width="150px" height="100px">
    <ul>
      <li><a href="#">Model S</a></li>
      <li><a href="#">Model 3</a></li>
      <li><a href="#">Model X</a></li>
      <li><a href="#">Model Y</a></li>
      <li><a href="#">Solar Proof</a></li>
      <li><a href="#">Solar Panels</a></li>
    </ul>
    <a class="btn" href="#">Shop</a>
    <a class="btn" href="#">Account</a>
    <a class="btn" href="#">Menu</a>
  </nav>
</header>
```

- CSS
```css
nav{
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    display: flex;
    align-items: center;
}

.logo{
    margin-left: 18px;
    cursor: pointer;
}

nav ul{
    flex: 1;
    text-align: center;
}

nav ul li{
    display: inline-block;
    margin: 10px 20px;
}

nav ul li a{
    text-decoration: none;
    color: black;
}

nav .btn{
    color: black;
    text-decoration: none;
    margin-right: 18px;
    padding: 10px;
}
```

---

**2. 배경에 model 3 이미지를 넣고 본문 텍스트를 만들었습니다.**
- HTML
```html
<div class="content">
  <h1>Model 3</h1>
  <p>Order Online for <u>Touchless Delivery</u></p>
</div>
```

- CSS
```css
body{
    font-family: Arial, Helvetica, sans-serif;
    margin: 0;
    padding: 0;
    background: url('car.jpg');
    background-size: cover;
}

.content{
    position: absolute;
    margin-left: 40%;
    margin-top: 7%;
}

.content h1{
    font-size: 50px;
}
```

---

**3. 본문 하단에 주문 및 인도 버튼을 만들었습니다.**
- HTML
```html
<div class="links">
  <a class="custom" href="#">CUSTOM ORDER</a>
  <a class="existing" href="#">EXISTING DELIVERY</a>
</div>
```

- CSS
```css
.links{
    position: absolute;
    margin-top: 42%;
    margin-left: 30%;
}

.links .custom{
    padding: 10px 80px;
    text-decoration: none;
    color: #fff;
    background-color: rgb(37, 37, 37);
    border-radius: 30px;
}

.links .existing{
    padding: 10px 80px;
    text-decoration: none;
    color: black;
    background-color: #fff;
    border-radius: 30px;
}
```

---

### 이미지 참조
- www.tesla.com
















