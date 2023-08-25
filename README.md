# AVeryPersonalReview (지극히 개인적인 리뷰 사이트)

### HTML이 주 요소인 프로젝트

## 개요

'HTML 요소를 극대화한 사이트를 만들수 있을까 / 어떤 주제가 좋을까' 라고 생각하다가, 가볍게 img, button 으로 이루어진(댓글 기능은 script와 db를 지원해야 할 것 같아서 뺏습니다. 그러다보니 클라이언트의 피드백을 받지못해 개인적인 리뷰 사이트라고 명칭을 만들었습니다.) 사이트가 적합하다고 생각되어 시작하였습니다.

## 희망사항

**Callout:** 다음 html 요소들을 이용해보고 싶습니다.

```html
<html>
  <head>
    <meta />
    <title>AVeryPersonalReview</title>
  </head>
  <body>
    <header>
      <nav></nav>
    </header>
    <main>
      <section>
        <img />
        <button></button>
      </section>
    </main>
    <footer></footer>
    <audio></audio>
  </body>
</html>
```

## 진행 내역

2021-05-03 (마지막 작업 이후 동결)

## 앞으로 할 일

1. style.css를 html 안에 넣어서 css파일이 존재하지 않도록 만들기

2. 색상이 안이뻐서 https://palettes.shecodes.io/ 에서 적합한 색상 찾고 적용하기

3. info 페이지 화면이 안이뻐서 다른 예시들 참고하며 수정하기

4. 후에 테스트해서 html 파일안에 style, script 요소를 넣에도 git에서 html파일로 인식할 경우, 약 20%정도만 사용해서(이왕이면 최소화) mongoDB Atras등의 webDB에 댓글 넣고 불러올 수 있게 구현해보는것도 좋을것.
