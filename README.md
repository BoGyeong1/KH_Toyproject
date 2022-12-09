# 💜 보솜 KH_TOY PROJECT 💜

## 🏨 L4 Hotel Survey 🏨

### 🌺 개요

- L4hotel을 이용한 고객들의 만족도를 조사하기 위한 설문 홈페이지를 작성

### 🌷 목표

- 이용만족도를 조사한 후 불편사항을 인지하고 개선

### 🍒 프로젝트 진행 기간

- 2022년 11월 10일 ~ 2022년 11월 11일
- 2022년 12월 08일 ~ 2022년 12월 09일

## 🍇 Team Member & Part

### 진보경

- [HTML] [index](./docs/HTMLs/index.html) / [join_membership](./docs/HTMLs/join_membership.html) / [statistics_first](/docs/HTMLs/statistic_first.html) / [statistics](./docs/HTMLs/statistics.html)
- [CSS] [index](./docs/CSSs/index.css) / [join_membership](./docs/CSSs/join_membership.css) / [statistics](./docs/CSSs/statistics.css)
- [Bootstraps] [index](./docs/bootstraps/index.html) / [statistics](/docs/bootstraps/staticstics.html) /[statistics_first](./docs/bootstraps/statistic_first.html)

### 김다솜

- [HTML] [login](./docs/HTMLs/login.html) / [period_stay](./docs/HTMLs/period_stay.html) / [survey](./docs/HTMLs/survey.html)
- [CSS] [login](./docs/CSSs/login.css) / [period_stay](./docs/CSSs/period_stay.css) / [survey](./docs/CSSs/survey.css)
- [Bootstraps] [login](./docs/bootstraps/login.html)/[period_stay](./docs/bootstraps/period_stay.html) /[survey](./docs/bootstraps/survey.html) / [join_membership](./docs/bootstraps/join_membership.html)

### 🍰 요구사항 정의서 & 화면 정의서

- [요구사항정의서](./docs/refers/bosom_demand.png)

- [화면정의서](./docs/refers/bosom_Wireframe.pdf)

### 🙈 IMAGE & 🙉 YOUTUBE VIDEO

- [IMAGE](./docs/refers/L4HOTEL_Home.png)

- [HTML YOUTUBE](https://youtu.be/475CGT6pGx0)

- [Bootstraps YOUTUBE](https://youtu.be/2uajpWv7ZP8)

### 프로젝트를 마무리하며 느낀 소감

- 진보경 : 오류가 났을 때 CSS 연결 주소를 잘 살펴봐야한다는 것. CSS는 정말 종류가 다양하다. 협력을 통해 잘 마무리 하여 다행이다.

- 김다솜 : 프론트쪽은 보여지는 것이기에 수행 하기에 조금은 쉽지 않을까 생각을 했었는데 어느 하나 쉬운것은 없으며 기능이라는 것은 상당히 방대하다는 것을 느꼈다.

## Study Publisings

- [HTMLs](./docs/HTMLs/index.html)
- [HTML CSSs](./docs/CSSs/index.css)
- [Bootstraps](./docs/bootstraps/index.html)
- [Bootstrap CSSs](./docs/bootstraps/CSSs/index.css)

### 주요 코드

- 메뉴코드  
  **flex-column flex-md-row**  
  화면을 줄였을때 메뉴가 로고 하단으로 내려오는 코드

```
<nav
          class="menu navbar navbar-expand d-flex flex-column flex-md-row fixed-top"
        >
          <div>
```

- 통계화면의 collapse 사이드바 메뉴  
  메뉴에 collapse 적용한 부분

```
<ul class="list-unstyled font-color">
              <div
                class="btn btn-toggle collapsed fs-5 fw-bold"
                data-bs-toggle="collapse"
                data-bs-target="#collapseTarget"
              >
                통계
              </div>

              <ul class="list-unstyled collapse" id="collapseTarget">
                <a
                  href="./staticstics.html"
                  class="rounded nav-link ms-3 fw-bold fs-5 font-color"
                  >문항별 통계</a
                >
              </ul>
```
