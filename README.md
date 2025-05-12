# 중나좋체

[배포처 바로가기](https://gongu.copyright.or.kr/gongu/wrt/wrt/view.do?wrtSn=13262134&menuNo=200023)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Joongnajoche`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Joongnajoche/Joongnajoche.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Joongnajoche/Joongnajoche.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'Joongnajoche';
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Joongnajoche/Joongnajoche-Light.woff2') format('woff2'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/Joongnajoche/Joongnajoche-Light.woff') format('woff'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/Joongnajoche/Joongnajoche-Light.otf') format('opentype'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/Joongnajoche/Joongnajoche-Light.ttf') format('truetype');
}
@font-face {
  font-family: 'Joongnajoche';
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Joongnajoche/Joongnajoche-Medium.woff2') format('woff2'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/Joongnajoche/Joongnajoche-Medium.woff') format('woff'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/Joongnajoche/Joongnajoche-Medium.otf') format('opentype'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/Joongnajoche/Joongnajoche-Medium.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Joongnajoche/subsets/Joongnajoche-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/Joongnajoche/subsets/Joongnajoche-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Joongnajoche", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
- ‘중나좋체’의 지적재산권은 (주)중고나라가 소유하고 있습니다.
- ‘중나좋체’는 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며 자유롭게 수정하고 재배포할 수 있습니다.
단, 글꼴 자체를 유료로 판매하는 것은 금지하며, 중나좋체 저작권 안내와 라이선스 전문을 포함해서 다른 소프트웨어와 번들하거나 재배포 또는 판매가 가능합니다.
중나좋체 라이선스 전문을 포함하기 어려울 경우, 중나좋체의 출처 표기를 권장합니다. 예시) 이 페이지에는 중고나라에서 제공한 중나좋체 폰트가 적용되었습니다.
- ‘중나좋체’를 사용한 인쇄물, 광고물(온/오프라인), 상품, CI/BI 등의 이미지는 중고나라의 마케팅을 위해 활용될 수 있습니다.
이를 원치 않는 사용자는 언제든지 당사에 요청하실 수 있습니다. 정확한 사용 조건은 다음페이지의 중나좋체 라이선스 전문을 참고하시기 바랍니다.
- 기타 문의 font@joonggonara.co.kr
```
