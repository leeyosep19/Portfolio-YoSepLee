# 포트폴리오

### 프론트 엔드 개발자입니다!!  ✨.

라이브 사이트입니다  [클릭 &rarr;데모 들어가기](https://portfolio-yo-sep.netlify.app/)

![Portfolio Gif](/images/my-port.png)


## 프론트 개발자가 되기위해서

- c언어 / Python / java 기초문법
- jsp
- html / css / JavaScript 
- React
- node.js
- MongoDB / Mysql
- netlify /AWS /heroku


## 프로젝트 구성

![Lighthouse Report](/images/Controller.png)
![Lighthouse Report](/images/shoppingmall.png)

### 자세한 내용은 [킅릭 &rarr;데모 들어가기](https://portfolio-yo-sep.netlify.app/)❤️.

## 시작 🚀

You'll need [Git](https://git-scm.com) to be installed on your computer. 
```
# Clone this repositoryㅍ
$ git clone https://github.com/leeyosep19/project-todo.git
```

Git이 설치되어 있지 않거나 터미널 사용이 마음에 들지 않으면 zip을 다운로드하여 압축을 풀고 원하는 코드 편집기에서 추출된 폴더를 열 수 있습니다.

### Header

In all of the places where you're supposed to fill your information you'll find HTML comments. As shown below just replace what is already in the opening and closing tags below the comment with your information.

```html
<div class="header__text-box row">
      <div class="header__text">
        <h1 class="heading-primary">
          <!-- Replace the following name with your name -->
          <span>lee yo Sep</span>
        </h1>
        <!-- Put a small paragraph about yourself -->
        <p>신입 프론트 엔드 개발자입니다!!</p>
        <a href="#contact" class="btn btn--pink">email 주소</a>
      </div>
    </div>
```

### Work Section

Each div with class `work__box` represents a project, replace the contents of the all the tags with the information of your projects.

```html
<div class="work__box">
    <div class="work__text">
    <h3>Portfolio Template</h3>
    <p>
        A free Open Source Portfolio for anyone to use for free.
    </p>
    <ul class="work__list">
        <li>HTML</li>
        <li>SCSS</li>
        <li>JavaScript</li>
        <li>Parcel</li>
    </ul>

    <div class="work__links">
        <a href="#" class="link__text">
        Visit Site <span>&rarr;</span>
        </a> 
        <a href="https://github.com/leeyosep19/project-todo.git" target="_blank">
        <img src="./images/github.svg" class="work__code" alt="GitHub">
        </a>
    </div>
    </div>
    <div class="work__image-box">
        <img
            src="./images/project-1.png"
            class="work__image"
            alt="Project 1"
        />
    </div>
</div>
```

For changing the screenshot:
- first place the image in `images/` folder and then in HTML replace the name in `src` with the name of your image.

- Recommended size for project image (1366 x 767px) also make sure the size of all  project images is the same.

```html
<img
    src="./images/name-of-your-image.png"
    class="work__image"
    alt="Project 1"
/>
```

### Clients Section

- Place the logos of the clients and companies that you have worked with in `images/` directory and then replace the name in `src` with the name of your logos accordingly.

- Make sure that you don't have whitespace on either side of the logos.

```html
<img
    src="./images/your-logo.png"
    class="client__logo"
    alt="Your Logo"
/>
```

### About Section

- Replace the contents in the below paragraph with information about yourself.
- Place a nice photo of yourself in the `images/` directory and then change the name in the src with your image name.

```html
section class="contact" id="contact">
    <div class="row">
      <h2>email 주소</h2>. 
      <div class="contact__info">
        <p>
          안녕하세요!!😺 신입 개발자 입니다!! <br>
          많이 배우고 성장할수있는 개발자가 되겠습니다!! <br>
          트렌드를 잘파악하고 따라가며 한발 앞서 갈수있는 개발자가 되겠습니다!!<br>
          한번 믿고 같이 일해보고시고 판단해 주십시요 실망시키지 않겠습니다!!<br>
          ↓ ↓ ↓ 
        
        </p>
        <!-- Replace the email with yours -->
        <a href="http://dytpqdytqp70@naver.com" class="btn">dytpqdytqp70@nver.com</a>
      </div>
    </div>
  </section>
```

### Contact Section

- Modify the paragraph to your likings.
- Replace the email with yours in the `href` anchor property and the text also.

```html
<section class="contact" id="contact">
    <div class="row">
      <h2>email 주소</h2>. 
      <div class="contact__info">
        <p>
          안녕하세요!!😺 신입 개발자 입니다!! <br>
          많이 배우고 성장할수있는 개발자가 되겠습니다!! <br>
          트렌드를 잘파악하고 따라가며 한발 앞서 갈수있는 개발자가 되겠습니다!!<br>
          한번 믿고 같이 일해보고시고 판단해 주십시요 실망시키지 않겠습니다!!<br>
          ↓ ↓ ↓ 
        
        </p>
        <!-- Replace the email with yours -->
        <a href="http://dytpqdytqp70@naver.com" class="btn">dytpqdytqp70@nver.com</a>
      </div>
    </div>
  </section>
```

### Footer

- Replace the `href` attribute values to your profile URLs for all anchors.
- Remove the div with class `footer__github-buttons`.

```html
<<footer role="contentinfo" class="footer">
    <div class="row">
      <!-- Update the links to point to your accounts -->
      <ul class="footer__social-links">
        <li class="footer__social-link-item">
          <a href="https://naver.com/dytpqdytqp70@naver.com/" title="Link to Twitter Profile">
            <img src="./images/naver_icon.png" class="footer__social-image" alt="Twitter">
          </a>
        </li>
        <li class="footer__social-link-item">
          <a href="https://github.com/leeyosep19/project-todo.git" title="Link to Github Profile">
            <img src="./images/github.svg" class="footer__social-image" alt="Github">
          </a>
        </li>
        <li class="footer__social-link-item">
          <a href="https://www.google.com/" title="Link to Codepen Profile">
            <img src="./images/icons8-구글-로고-48.png" class="footer__social-image" alt="Codepen">
          </a>
        </li>        
      </ul>

      <!-- If you give me some credit by keeping the below paragraph, will be huge for me 😊 Thanks. -->
      <p>
        &copy; 2024 - Template designed & developed by <a href="https://nisar.dev" class="link">Nisar</a>.
      </p>
      <div class="footer__github-buttons">
        <iframe
          src="https://ghbtns.com/github-btn.html?user=nisarhassan12&repo=portfolio-template&type=watch&count=true"
          frameborder="0" scrolling="0" width="170" height="20" title="Watch Portfolio Template on GitHub">
        </iframe>
      </div>
    </div>
  </footer>
```
